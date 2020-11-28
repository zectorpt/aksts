# aksts
AKS Troubleshooting

kubectl create deployment --image=jomedei/aksts:withsleep akstsdpl
kubectl get pods

#NAME                        READY   STATUS    RESTARTS   AGE
#akstsdpl-7b945f46fb-dc8gd   1/1     Running   0          3s

kubectl exec -it akstsdpl-7b945f46fb-dc8gd -- /bin/bash
