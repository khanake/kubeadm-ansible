# This is Anbisle for kubeadm initial node setting
Only tested Ubuntu 20.04 lts

## How to use
- Prepare control plane and node.
- Modify inventory file for your remote node.
- Then type below command.
```
## setup for control plane
ansible-playbook -i inventory cp.yml

## setup for node
ansible-playbook -i inventory nd.yml
```

## Reference(2021/10/17)
[Docker install guide](https://kubernetes.io/docs/setup/production-environment/container-runtimes/)

[Kubeadm install guide](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/install-kubeadm/)