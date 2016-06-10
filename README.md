# install android studio and friends on a ubuntu 16 host

sudo apt-get install git ansible
git clone https://github.com/skarlsson/ubuntu_android_dev.git
cd ubuntu_android_dev

ansible-playbook -i "localhost," -c local android-dev.yml
