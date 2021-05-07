# gitops-examples

# ARGOCD CLI

# VERSION=$(curl --silent "https://api.github.com/repos/argoproj/argo-cd/releases/latest" | grep '"tag_name"' | sed -E 's/.*"([^"]+)".*/\1/')
# VERSION=v2.0.1
# curl -sSL -o /usr/local/bin/argocd https://github.com/argoproj/argo-cd/releases/download/$VERSION/argocd-linux-amd64
# chmod +x /usr/local/bin/argocd
# argocd login argocd-server-argocd.apps.ocptest.konsalt.info
# argocd cluster list
# argocd cluster add default
# argocd cluster list
