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

### Vagrant

* [base box](https://www.vagrantup.com/docs/boxes/base)



### Ubuntu

* [Autoinstall](https://ubuntu.com/server/docs/install/autoinstall-quickstart)


