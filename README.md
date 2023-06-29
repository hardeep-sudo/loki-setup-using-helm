# loki-setup-using-helm
INSTALL

$ kubectl create ns loki

$ helm template --release-name=loki-sandbox --namespace=loki -f values.yaml .| kubectl apply -f
