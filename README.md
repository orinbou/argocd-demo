# argocd-demo
k8s gitops demo for ArgoCD

# ArgoCDインストール
名前空間を作成する。
```
kubectl create namespace argocd
```
ArgoCDをインストールする。
```
kubectl apply -n argocd -f argocd/install.yaml
```
※[インストール用yaml](https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml)の取得元は[ArgoCD公式ページ](https://argoproj.github.io/argo-cd/)の「Getting Started」を参照してください。
