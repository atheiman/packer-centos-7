# Packer Examples

This is a collection of [Packer](https://www.packer.io/) machine image builder examples.

## [centos-7-minimal](./centos-7-minimal)

Minimal CentOS 7 image built in VirtualBox from a `.iso` image and a kickstart config file.

## ubuntu-1604-minimal

Minimal Ubuntu 16.04 LTS image built in VirtualBox from a `.iso` image and a kickstart config file.
https://releases.ubuntu.com/16.04/ubuntu-16.04.4-server-amd64.iso
0a03608988cfd2e50567990dc8be96fb3c501e198e2e6efcb846d89efc7b89f2

## centos-7-hardened

Minimal CentOS 7 image built in VirtualBox from a `.iso` image and a kickstart config file that builds filesystems and disks according to [CIS Benchmark specifications](https://www.cisecurity.org/cis-benchmarks/).

## ubuntu-1604-hardened

Minimal Ubuntu 16.04 LTS image built in VirtualBox from a `.iso` image and a kickstart config file that builds filesystems and disks according to [CIS Benchmark specifications](https://www.cisecurity.org/cis-benchmarks/).

## chef-solo-provisioned

CentOS 7 image customized with the [chef-solo Packer provisioner](https://www.packer.io/docs/provisioners/chef-solo.html) and verified after build using inspec.

## Thanks

This work builds off of the examples [geerlingguy/packer-centos-7](https://github.com/geerlingguy/packer-centos-7) and [geerlingguy/packer-ubuntu-1604](https://github.com/geerlingguy/packer-ubuntu-1604).
