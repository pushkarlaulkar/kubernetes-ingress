This repo contains all files for a bsic kubernetes ingress deployment.

After the repository is cloned run below command to create all resources

```
kubectl create -f .
```
The ingress resource has 2 rules

http://<any k8's node ip>:30080/nginx1 will give nginx1 as output

http://<any k8's node ip>:30080/nginx2 will give nginx2 as output

http://<any k8's node ip>:30080 will give default-backend as output
