apiVersion: argoproj.io/v1alpha1
kind: ApplicationSet
metadata:
  name: guestbook-argo-app
  namespace: argocd
spec:
  generators:
  - list:
      elements:
      - app: nginx
        repoURL: https://github.com/mitkar241/helm.git
        path: charts/nginx-app
        branch: main #HEAD
  template:
    metadata:
      name: '{{app}}-guestbook'
    spec:
      project: default
      # Source of the application manifests
      source:
        repoURL: '{{ repoURL }}'  # Can point to either a Helm chart repo or a git repo.
        targetRevision: '{{ branch }}'  # For Helm, this refers to the chart version.
        path: '{{ path }}'  # This has no meaning for Helm charts pulled directly from a Helm repo instead of git.
      # Destination cluster and namespace to deploy the application
      destination:
        server: https://kubernetes.default.svc
        # The namespace will only be set for namespace-scoped resources that have not set a value for .metadata.namespace
        namespace: guestbook
      syncPolicy:
        syncOptions:
        - CreateNamespace=true
        automated:
          selfHeal: true
          prune: true
 
