<h1 align="left">
GitOps - ArgoCD
</h1>

<h1 align="left">
🚀🚀🚀
</h1>

<br>

- [Innovations Brought by Automated Deployment with GitOps and ArgoCD in Kubernetes](#innovations-brought-by-automated-deployment-with-gitops-and-argocd-in-kubernetes)

<br>

## Innovations Brought by Automated Deployment with GitOps and ArgoCD in Kubernetes

<br>

Hyper-V üzerinde bir Master node ve iki Worker node'dan oluşan Kubernetes cluster üzerinde GitOps ve ArgoCD'yi kullanarak otomatik deployment yapılmasını sağlamaktadır.

<br>

Image olarak hasangural/nginx-status container image'ı kullanılarak bir deployment oluşturulmuş ve bu deployment MetalLB ve Ingress aracılığıyla dış dünyaya açılmıştır.

<br>

GitHub ile entegre edilen ArgoCD GitHub repository'sine yapılan her commit ile otomatik olarak Kubernetes cluster üzerinde ilgili değişiklikleri uygular.

<br>

Kubectl komutlarına gerek kalmadan yalnızca YAML dosyalarını GitHub'a ekleyerek uygulamaların dağıtımını otomatikleştirmeyi amaçlamaktadır.