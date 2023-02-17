```

cd terraform
terraform init
terraform apply

# comes from execution
export KUBECONFIG=

helm install argocd --namespace argocd --create-namespace  argo/argo-cd

kubectl apply -f https://raw.githubusercontent.com/kubernickels/test-repo/main/registry/registry.yaml
```