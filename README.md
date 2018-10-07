# Set up Local Mac
Ensure Apple's command line tools are installed (xcode-select --install)

1)Install Pip : sudo easy_install pip

2)Use Pip to install ansible : sudo pip install ansible

Clone this repository to your local drive

Run ansible-playbook -K mac_setup.yml inside this directory to install required Ansible roles.

Note : Use for older pip & Macs : curl https://bootstrap.pypa.io/get-pip.py | sudo python
