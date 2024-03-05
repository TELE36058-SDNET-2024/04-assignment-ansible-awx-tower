
## AWX on Single Node K3x
Special thanks to @kurokobo https://github.com/kurokobo/awx-on-k3s these steps and code are from his repo. I am just making an ubuntu version for my lab.

An example implementation of AWX on single node K3s using AWX Operator, with easy-to-use simplified configuration with ownership of data and passwords.


## Environment
* Ubuntu 22.04 (Minimal)
* K3s v1.28.5+k3s1
* Products that will be deployed:
* AWX Operator 2.10.0
* AWX 23.6.0
* PostgreSQL 13

## Quick Guide
If you want to install ansible awx quickly just use the install.sh script just download the install.sh file

Note: the default config uses awx.example.com you can change this if you edit the install.sh

wget https://raw.githubusercontent.com/maniak-academy/guide-k3s-awx-tower/main/install.sh
chmod +x install.sh
sudo ./install.sh

## To view your IP address 

kubectl -n awx get awx,all,ingress,secrets

Output:

```
ingress.networking.k8s.io/awx-ingress   traefik   awx.example.com   172.16.10.2   80, 443   2m51s
```

## You need to use DNS to get access to your cluster
So make sure you dns or hosts files are setup for awx.exmaple.com or what you set it too.