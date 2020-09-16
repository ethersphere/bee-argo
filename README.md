# Bee-ArgoCD

This repo is used by ArgoCD for automatic deployments to different bee environments.
Generate k8s yamls with
`helm template bee -n bee ethersphere/bee -f edge-bee.yaml --no-hooks --set image.digest={DIGEST} > edge/bee.yaml`
