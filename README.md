# Set up Local Mac
Ensure Apple's command line tools are installed (xcode-select --install)

1)Install Pip : sudo easy_install pip

2)Use Pip to install ansible : sudo pip install ansible

Clone this repository to your local drive

Run ansible-playbook -K mac_setup.yml inside this directory to install required Ansible roles.

3)The brew cask install docker should have installed docker
a)Cmd-space to open Docker and see the whale ; Accept to run as priviledged user

4)Using Docker:
a)To Build the image :
docker build -t test_image
b)To Run the image :
docker run -it --rm --name=test_image ubuntu

Note : Use for older pip & Macs : curl https://bootstrap.pypa.io/get-pip.py | sudo python
