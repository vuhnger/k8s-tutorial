# K8s tutorial

Tutorials and experiments related to learning Kubernetes for my thesis.

AI declaration: No AI is used to modify files in this repository. AI was used to ideate ways to learn, debug and verify configuration files and code, but in read-only modes.

## Resources used

- [Kubernetes tutorials](https://kubernetes.io/docs/tutorials/)
- [Alta3 YouTube](https://www.youtube.com/watch?v=MTHGoGUFpvE)
- [TLDR](https://tldr.sh/) for checking cli reference docs on the fly.

## Commands

- `minikube start` - Start the K8s API Server
- `kubectl apply -f <file>` - Create or modify pod(s) from a manifest file specified with -f.
- `kubectl apply -f <folder>` - Create or modify pod(s) from all manifests within the folder.
- `kubectl get pods` - Shows the currently running pods, with flags to specify which namespace etc.
- `kubectl describe <resource> <name>` - Describes a resource in detail, e.g a Pod.
- `kubectl delete <resource> <name>` - Delete a resource by name
- `kubectl delete -f <file>` - Delete resource(s) by file
- `kubectl get namespace` - Lists namespaces
- `kubectl create ns` - Creates a new namespace
