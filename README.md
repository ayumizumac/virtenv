# virtualenvs
virtual environments. first of all, target cpu is intel. I will separate tree for apple M1/M2 cpu.

make virtual env as vagrant instance.

# initialize

when you up vagrant, you should do following command.

`kubeadm init --pod-network-cidr=192.168.25.0/24`

# next action

`mkdir -p $HOME/.kube`
`cp -i /etc/kubernetes/admin.conf $HOME/.kube/config`
`chown $(id -u):$(id -g) $HOME/.kube/config`

# add SSH token

[see also](https://donachikiblog.com/github-authentication-failed/)

