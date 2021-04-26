# aksts
AKS Troubleshooting <br>

kubectl create deployment --image=jomedei/aksts akstsdpl <br>
kubectl get pods <br>

#NAME                        READY   STATUS    RESTARTS   AGE <br>
#akstsdpl-7b945f46fb-dc8gd   1/1     Running   0          3s <br>

kubectl exec -it akstsdpl-7b945f46fb-dc8gd -- /bin/bash <br>
