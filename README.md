# k8s-demo-app

Get the Ip address in Ubuntu `Hostname -I` or `ip addr | grep -i inet`
 kubectl commands

 kubectl get pods, services, rs, deployments

 kubectl describe <> <name>
 kubectl log <> <name>
 kubectl create -f worker-pod.yml 
  kubectl get pods
   52  kubectl get service
   53  kubectl describe service db
   54  kubectl get pods
   55  kubectl edit pods worker-pod 
   56  kubectl get pods
   57  kubectl logs worker-pod 
   58  kubectl describe pods worker-pod 
   59  kubectl delete pods worker-pod 
   60  vi worker-pod.yml 
   61  kubectl create -f worker-pod.yml 
   62  kubectl get pods
   63  kubectl describe pods worker-pod 
   64  kubectl get rs
   65  kubectl get deployments.apps 
   66  kubectl get service