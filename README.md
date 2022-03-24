# efk-configure

## flunetd  
kubectl apply -f fluentd-cm.yaml  
kubectl apply -f fluentd-daemonSet.yaml  

## es  
kubectl apply -f es-pv.yaml  
kubectl apply -f es-storage.yaml  
kubectl apply -f es-svc.yaml  
kubectl apply -f es-statefulSet.yaml  
  
## kibana  
kubectl apply -f kibana-deployment.yaml  
kubectl apply -f kibana-svc.yaml  

