## Others

Here is a collection of links to other Kubernetes tools that work well with k14s collection:

- [https://github.com/robscott/kube-capacity](https://github.com/robscott/kube-capacity)
  - Provides a way to understand resources footprint
  - `kube-capacity -p -l -u $(kapp label -a cf --tty=false)`

### Misc

- [Minikube](https://kubernetes.io/docs/tasks/tools/install-minikube/)
  - Minikube is very convenient to use for development since it comes with built-in Docker daemon
- [Docker CLI binaries](https://docs.docker.com/install/linux/docker-ce/binaries/)
  - Official location where to grab Docker CLI binaries; useful with using Minikube
