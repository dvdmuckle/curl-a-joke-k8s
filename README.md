# curl-a-joke-k8s
Curl-a-joke K8s deployment, service, and ingress
### Usage
``` bash
cd curl-a-joke-k8s
kubectl apply -f curl-a-joke-all.yaml
```
If you'd like to deploy individual commponents of the stack (deployment, service, ingress) separately, you may use the individual files provided for each.


If you're deploying to a Pi cluster, use the `rpi` branch, or just modify the image used in `curl-a-joke-deploy.yaml` or `curl-a-joke-all.yaml` to use the `armhf` tag.
