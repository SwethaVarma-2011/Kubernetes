Commands related to the Kubernetes

# kubectl run --image <I_N> <P_N> ----- to create pod along with the container      (Where I_N = image name of the container , P_N = creating pod name)
# kubectl create -f pod-defination.yml ---- To create pods with containers, with the container image as mentioned in yml file
# kubectl get pods -- to see list of pods
# kubectl get pods -o wide ----- To see list of pods and whicg pod is running on which node
# kubectl get nodes -- to see list of nodes
# kubectl get nodes -o wide --- To list complete information about nodes including ip addresses.
# kubectl replace -f replication-controller.yml / kubectl scale --replicas==* -f replication-controller.yml  --- to increase/decrease pods
# kubectl delete -f <F_N> -- to delete pods in that file
# kubectl delete --all pods --- to delete all pods in that master
