# kubernetes

git clone https://github.com/carlosesdias/kubernetes.git


# Generic Virtual Machine
## Networking
export PRIVATE_IP=x.x.x.x

export PRIVATE_NETMASK=24

export PUBLIC_IP=y.y.y.y

export PUBLIC_NETMASK=24

export PUBLIC_GATEWAY_IP=z.z.z.z

export PUBLIC_DNS_IP=8.8.8.8


## Kubernetes Cluster
export POD_NETWORK=10.2.0.0/16

export SERVICE_IP_RANGE=10.3.0.0/24

export K8S_SERVICE_IP=10.3.0.1

export DNS_SERVICE_IP=10.3.0.10


# Digital Ocean

## Networking
export PRIVATE_IP=\$private_ipv4

export PUBLIC_IP=\$public_ipv4

## Kubernetes Cluster
export POD_NETWORK=10.2.0.0/16

export SERVICE_IP_RANGE=10.3.0.0/24

export K8S_SERVICE_IP=10.3.0.1

export DNS_SERVICE_IP=10.3.0.10
