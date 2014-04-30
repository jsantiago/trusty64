Install [Virtualbox][1]

Install [Vagrant][2]

Install [Ansible][3]:

    brew install ansible

Start machine:

    vagrant up

Adjust playbook.yml and re-provision as necessary

    vagrant provision

Package up the vagrant box:

    vagrant package --output trusty64.box


[1]: https://www.virtualbox.org/wiki/Downloads
[2]: http://www.vagrantup.com/downloads
[3]: http://docs.ansible.com/intro_installation.html
