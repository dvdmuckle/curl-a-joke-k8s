# curl-a-joke-k8s
Curl-a-joke K8s deployment, service, and ingress
### Usage
``` bash
cd curl-a-joke-k8s
kubectl apply -f curl-a-joke.yaml
```

If you're deploying to a Pi cluster, use the `rpi` branch, or just modify the image used in `curl-a-joke.yaml` to use the `armhf` tag.
