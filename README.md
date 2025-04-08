[Ondrej Sika (sika.io)](https://sika.io) | <ondrej@sika.io> | [__Skoleni Kubernetes__](https://ondrej-sika.cz/skoleni/kubernetes/), [__Skoleni ArgoCD__](https://ondrej-sika.cz/skoleni/argocd/) 🚀💻

> [!TIP]
> <a href="https://ondrej-sika.cz/skoleni/argocd"><img src="https://img.shields.io/badge/Školení%20ArgoCD-by%20Ondřej%20Šika-orange?style=for-the-badge&logo=argo&logoColor=white" style="width: 100%; height: auto;" alt="Školení ArgoCD by Ondřej Šika" /></a>
>
> 🚀 Naučte se, jak efektivně spravovat deploymenty pomocí **ArgoCD**! Praktické školení vedené [Ondřejem Šikou](https://ondrej-sika.cz).
>
> 👉 [Více informací a registrace zde](https://ondrej-sika.cz/skoleni/argocd)

# cloud-native-bratislava-argocd

[sika.link/cnb-argocd](https://sika.link/cnb-argocd)

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
