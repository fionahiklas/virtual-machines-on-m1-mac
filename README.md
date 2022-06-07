# Virtual Machines on M1 Mac

## Overview

Being able to create a Linux (or other) VM on a Mac either maually or using
`vagrant` or similar has been really handy.  At the time of writing it's 
not as easy on an M1 Mac


## Packer

You can download the packer executable but it seems easier to install using homebrew
as per the instructions on the download page

```
brew tap hashicorp/tap
brew install hashicorp/tap/packer
```




## References

### Packer

* [packer download](https://www.packer.io/downloads)
* [qemu builder](https://www.packer.io/plugins/builders/qemu)
* [vagrant builder](https://www.packer.io/plugins/builders/vagrant)
* [packer example](https://github.com/chef/bento/blob/main/packer_templates/ubuntu/ubuntu-22.04-amd64.json)
* [Packer example with qemu_binary](https://github.com/mcandre/packer-templates/blob/issue-153/debian/debian-arm64.json)
* [Packer Debian examples](https://github.com/mcandre/packer-templates/tree/issue-153/debian)
* [Packer fails to boot](https://serverfault.com/questions/959677/packer-errors-with-qemu-system-aarch64)


### Vagrant

* [base box](https://www.vagrantup.com/docs/boxes/base)


### Qemu

* [Machine types for ARM](https://www.qemu.org/docs/master/system/target-arm.html)

### Ubuntu

* [Autoinstall](https://ubuntu.com/server/docs/install/autoinstall-quickstart)
* [Mirror ISO images](https://www.mirrorservice.org/sites/cdimage.ubuntu.com/cdimage/releases/22.04/release/)

