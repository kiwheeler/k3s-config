## k3s-config

copy /etc/rancher/k3s/config.yaml

## Longhorn##
**If needed add longhorn repository**
helm repo add longhorn https://charts.longhorn.io
create longhorn-system namespace
install longhorn helm chart

## Metal LB##
**If needed add repository**
install 
create metallb-system namespace
**Refer to helm output - confgiure install-specific config file e.g. metallb-1626842500-config**
