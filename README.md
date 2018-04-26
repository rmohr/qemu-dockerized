# k8s clusters in qemu in docker

* `base` contains the base image with some scripts, qemu and dnsmasq
* `centos7` adds a vagrant centos7 box to the image
* `cli` contains a tool for provisioning, running and managing the containerized clusters
* `k8s-1.9.3` k8s-1.9.3 cluster based on the centos7 image, provisioned with kubeadm
* `os-3.9` os-3.9 cluster based on the centos7 image, provisioned with openshift-ansible

## Versions to use

* `kubevirtci/cli`: `sha256:1dd015dea4f12e6dcb8e31be3eeb677fed96f290ef4a4892a33c43d666053536`
* `kubevirtci/base`: `sha256:67b84e2acefdcd7197989cbab1f2d1324eb87b5a77bd31d52d3000d13eee750c`
* `kubevirtci/centos:1802_01`: `sha256:31a48682e870c6eb9a60b26e49016f654238a1cb75127f2cca37b7eda29b05e5`
* `kubevirtci/os-3.9.0:`: `sha256:d55fc1bef8a9ab327c5f213deec75ad9cc3a1c258593b9fd966b11bef6010bd6`
* `kubevirtci/os-3.9.0-crio:`: `sha256:37e16b5545078e96b9eeb913c3e66205b14440974b345692e55e2c9560b8dbac`
* `kubevirtci/k8s-1.9.3:`: `sha256:2ea1e772b13067617a7fc14f14105cfec5f97dd6e55db1827c3e877ba293fa8d`
