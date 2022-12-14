# Argo CD - Declarative Continuous Delivery for Kubernetes
---
<img src="https://cncf-branding.netlify.app/img/projects/argo/horizontal/color/argo-horizontal-color.png" alt="argocd-logo" width="400" height="200" alt="helm-logo" />

Declarative continuous deployment for Kubernetes

## TODO
---
- [ ] Research production level folder structure
- [ ] Move to separate directory
- [ ] Try kustomize and other k8s tools
- [ ] How to pull Helm charts and override files from separate repos

## Resources
---
- [ ] [github - argoproj/argo-cd](https://github.com/argoproj/argo-cd)
- [ ] [argo-cd.readthedocs.io](https://argo-cd.readthedocs.io/en/stable/)
- [ ] [techtarget - Learn to use Kubernetes CRDs in this tutorial example](https://www.techtarget.com/searchitoperations/tip/Learn-to-use-Kubernetes-CRDs-in-this-tutorial-example)
- [ ] [padok - Quick introduction to ArgoCD ApplicationSet](https://www.padok.fr/en/blog/introduction-argocd-applicationset)
- [ ] [github - christianh814/gitops-examples](https://github.com/christianh814/gitops-examples)
- [ ] youtube - `applicationset argocd`
- [ ] [youtube - Argo Proj - ArgoCon '21 - Argo CD Production Best Practices](https://www.youtube.com/watch?v=ESQLqjbM8h0)
- [ ] [argo-cd -Generating Applications with ApplicationSet](https://argo-cd.readthedocs.io/en/stable/user-guide/application-set/)
- [ ] [medium - How to create ArgoCD Applications Automatically using ApplicationSet? “Automation of GitOps”](https://amralaayassen.medium.com/how-to-create-argocd-applications-automatically-using-applicationset-automation-of-the-gitops-59455eaf4f72)
- [ ] [github - AmrAlaaYassen/ArgoCD-ApplicationSet-Demo](https://github.com/AmrAlaaYassen/ArgoCD-ApplicationSet-Demo)
- [ ] [argocd-applicationset - Git Generator](https://argocd-applicationset.readthedocs.io/en/stable/Generators-Git/)
- [ ] [argo-cd - Git Generator](https://argo-cd.readthedocs.io/en/stable/operator-manual/applicationset/Generators-Git/)
- [ ] [argo-cd - Helm](https://argo-cd.readthedocs.io/en/stable/user-guide/helm/)
- [ ] [omegion - How to install ArgoCD on Kubernetes cluster](https://omegion.dev/2021/06/how-to-install-argocd-on-kubernetes-cluster/)
- [ ] [medium - Level Up Your Argo CD Game with ApplicationSet](https://itnext.io/level-up-your-argo-cd-game-with-applicationset-ccd874977c4c)
- [ ] [github - xsreality/argocd-applicationset-demo](https://github.com/xsreality/argocd-applicationset-demo)
- [ ] [github - omegion/echo-k8s-app](https://github.com/omegion/echo-k8s-app)
- [ ] [argo-cd - Best Practices](https://argo-cd.readthedocs.io/en/stable/user-guide/best_practices/)
- [ ] [github - stevesea/argocd-helm-app-of-apps-example](https://github.com/stevesea/argocd-helm-app-of-apps-example)
- [ ] [opensource - Automatically create multiple applications in Argo CD](https://opensource.com/article/21/7/automating-argo-cd)
- [ ] [suedbroecker - How to deploy an application with argo cd using a helm repository](https://suedbroecker.net/2022/07/22/how-to-deploy-an-application-with-argo-cd-using-a-helm-repository/)
- [ ] [stackoverflow - Templates and Values in different repos via ArgoCD](https://stackoverflow.com/questions/73023423/templates-and-values-in-different-repos-via-argocd)
- [ ] *argocd production best practices*
  - [ ] [argo-cd - Best Practices](https://argo-cd.readthedocs.io/en/stable/user-guide/best_practices/)
  - [ ] [codefresh - Argo CD Best Practices](https://codefresh.io/blog/argo-cd-best-practices/)

## Description
---
Argo CD is one of the top GitOps continues delivery tools for Kubernetes in Cloud Native ecosystem nowadays.

Argo CD  implements GitOps Pull Model where it track any changes in source repos and sync/deploy the changes automatically into the destination clusters.

## Why Argo CD
---
Application definitions, configurations, and environments should be declarative and version controlled. Application deployment and lifecycle management should be automated, auditable, and easy to understand.
