# ansible-kuber-centos
deploy kuberntes to centos using binary way

# prepare
download etcd and kubernets binary files , copy them to files fold of roles.

# how to use it
run ansible k8s.yml in root fold of this project

# binary file
- on node nodes, kubectl kube-proxy kubelet kubeadm are needed
- on master nodes, kubectl kube-proxy kubelet api-server kube-scheduler kubeadm kube-controller


