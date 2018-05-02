This document explains how to connect to kubernetes cluster from the user side
**Note:** you must have a valid config file to connect to the cluster that will be provided to you along with the namespace to use
1- install kubectl, you can refer to the documentation for instruction on installation 
https://kubernetes.io/docs/tasks/tools/install-kubectl/
2- place the config file in the directory `~/.kube` (create the directory if it doesn't exist) 
3- install helm, you can refer to the documentation for instruction on installation
https://docs.helm.sh/using_helm/#installing-helm
4- run the following command and replace <name_space> with the name space provided to you
```
helm init --tiller-namespace <name_space>
```
