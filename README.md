# kubernetes workspace

This repository is a personal learning page.
I write my result of operation and management of kubernetes (k8s).

## environment

| Name | Version  
|------|---|
| host OS | Windows 11
| guest OS | centOS 7
| VirtualBox | 6.1.32
|docker server | 1.13.1
|docker client | 1.13.1
|kubeadm | 1.23.5
|CNI | calico 3.3

### cluster

| Name | IP address  
|------|---|
|k8s-master | 192.168.56.101
|k8s-node-1 | 192.168.56.102
|k8s-node-2 | 192.168.56.103

## install

1. [kubeadmのインストール](./kubeadm/install.md)

## security

1. [[Kubernetes]コンテナでのセキュリティ対策](./security/k8s_security.md)