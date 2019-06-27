# myKubernetes
This repository contains helper commands and setup tips to work with Kubernetes cluster

# kubectl docs
https://kubectl.docs.kubernetes.io/

# Set Auto complete for kubectl
Setup autocomplete in bash into the current shell, bash-completion package should be installed first.</br>
source <(kubectl completion bash) </br>

Add autocomplete permanently to your bash shell.</br>
echo "source <(kubectl completion bash)" >> ~/.bashrc

# list api-resources
  $ kubectl api-resources </br>
