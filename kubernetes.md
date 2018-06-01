## Kubernetes

### Tutorials
- https://kubernetes.io/docs/tutorials/kubernetes-basics/

### In depth and best practices
- https://stripe.com/blog/operating-kubernetes
- https://kubernetes.io/docs/concepts/configuration/overview/

### Notes
- Cluster: master, node(s). Nodes run "kubelet": the k8s agent, which communicates with the master via the "k8s API". Other software can use this API to interact with the cluster. Nodes also run the container daemon/runtime used to run software on them, e.g. Docker.
- Minikube: CLI for managing local clusters for dev etc. Backed by xhyve / VirtualBox / etc for the VM to run the node(s) on.
- kubectl: CLI for managing kubernetes clusters.
- "Deployment" instructions to k8s master for deploying and manaing your app. Kubernetes Deployment Controller watches machines ("nodes"), and re-schedules containers from unhealthy machines to healthy ones.
-

### Talks
- Kubernetes for Sysadmins – Kelsey Hightower at PuppetConf 2016: https://www.youtube.com/watch?v=HlAXp0-M6SY
