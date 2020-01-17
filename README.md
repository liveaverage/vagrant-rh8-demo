# vagrant-rh8-demo

Spin-up and evaluate your own RHEL8 VM using Vagrant

# Requirements

- Ansible installed/available on your installation host
- VirtualBox or another Vagrant-supported hypervisor
- [Red Hat Developer Subscription](https://developers.redhat.com/articles/getting-red-hat-developer-subscription-what-rhel-users-need-know/)

# Usage

- Fork this repo
- Clone repo to a system meeting aforementioned requirements and `cd` to that directory
- Update the [subscription details for your VM](https://github.com/liveaverage/vagrant-rh8-demo/blob/master/prep_vm.yml#L20)
  ```
  subscription-manager register --org=YOURORG --activationkey=YOURKEY --force
  ```
- Execute `vagrant up` from working directory
