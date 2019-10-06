# myKubernetes
This repository contains helper commands and setup tips to work with Kubernetes cluster

# kubectl docs
https://kubectl.docs.kubernetes.io/

# Set Auto complete for kubectl
Setup autocomplete in bash into the current shell, bash-completion package should be installed first.</br>
$ source <(kubectl completion bash) </br>

Add autocomplete permanently to your bash shell.</br>
$ echo "source <(kubectl completion bash)" >> ~/.bashrc

# list api resources/services
  $ kubectl api-resources </br>
  $ kubectl get apiservice </br>

  # Cluster info dump
  To get the whole cluster information </br>
  $ kubectl cluster-info dump

![picture alt](https://www.cncf.io/wp-content/uploads/2018/03/CNCF_TrailMap_latest.png "CNCF_Trail MAP")
