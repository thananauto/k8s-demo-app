# k8s-demo-app

Get the Ip address in Ubuntu `Hostname -I` or `ip addr | grep -i inet`
 kubectl commands

 kubectl get pods, services, rs, deployments


### kubectl apply commands in order
    
    kubectl apply -f mongo-secret.yaml
    kubectl apply -f mongo.yaml
    kubectl apply -f mongo-configmap.yaml 
    kubectl apply -f mongo-express.yaml

### kubectl get commands

    kubectl get pod
    kubectl get pod --watch
    kubectl get pod -o wide
    kubectl get service
    kubectl get secret
    kubectl get all | grep mongodb

### kubectl debugging commands

    kubectl describe pod mongodb-deployment-xxxxxx
    kubectl describe service mongodb-service
    kubectl logs mongo-express-xxxxxx

### give a URL to external service in minikube

    minikube service mongo-express-service


Mongo-express defautl credentials: admin:pass