# cloud-native-bratislava-argocd

## Ondrej Sika

- <ondrej@sika.io>
- [sika.io](https://sika.io)

## My Courses

- Kubernetes - https://www.ondrej-sika.cz/skoleni/kubernetes/
- ArgoCD - https://www.ondrej-sika.cz/skoleni/argocd/

## ArgoCD

- https://argoproj.github.io/cd/
- https://argo-cd.readthedocs.io/en/stable/

Install ArgoCD

```
make install-argocd
```

Apply App-of-Apps

```
kubectl apply -f cluster/sikademo/app_of_apps.yaml
```

See ArgoCD UI

https://argocd.k8s.sikademo.com
