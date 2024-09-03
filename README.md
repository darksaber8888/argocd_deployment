Argo CD provides Continuous Delivery tooling that automatically synchronizes and deploys your application whenever a change is made in your GitHub repository. By managing the deployment and lifecycle of an application, it provides solutions for version control, configurations, and application definitions in Kubernetes environments, organizing complex data with an easy-to-understand user interface. It can handle several types of Kubernetes manifests, including Jsonnet, Kustomize applications, Helm charts, and YAML/json files, and supports webhook notifications from GitHub, GitLab, and Bitbucket.

**Step 1 — Installing Argo CD on Your Cluster**

kubectl get nodes
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
