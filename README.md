# myKubernetes

This repository contains helper commands and setup tips to work with Kubernetes cluster

# Set Auto complete for kubectl
source <(kubectl completion bash) # setup autocomplete in bash into the current shell, bash-completion package should be installed first.</br>
echo "source <(kubectl completion bash)" >> ~/.bashrc # add autocomplete permanently to your bash shell.</br>

# list api-resources

  $ kubectl api-resources </br>
