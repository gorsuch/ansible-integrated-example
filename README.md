ansible-integrated-example
==========================

An example of ansible + git submodules

## Demo

```sh
# check out this repo, use --recursive to capture submodules, too
$ git clone --recursive git@github.com:gorsuch/ansible-integrated-example.git
...
# launch vagrant
$ vagrant up
...
# launch a docker container
$ vagrant ssh -c 'sudo docker run -t -i ubuntu /bin/bash'
Unable to find image 'ubuntu' locally
Pulling repository ubuntu
6006e6343fad: Download complete 
d2099a5ba6c5: Download complete 
cc0067db4f11: Download complete 
3db9c44f4520: Download complete 
5cf8fd909c6c: Download complete 
7656cbf56a8c: Download complete 
511136ea3c5a: Download complete 
086a54ed1641: Download complete 
5e9838970f44: Download complete 
c47d897f1a44: Download complete 
845a7ff0bf5a: Download complete 
6cfa4d1f33fb: Download complete 
101e9f33c3dc: Download complete 
35f6dd4dd141: Download complete 
e41f31e92d60: Download complete 
a6c8f8708259: Download complete 
53e0ea871c5d: Download complete 
9425702d2b8b: Download complete 
ac4bfb69e710: Download complete 
42ffda5fb276: Download complete 
902710ffbd62: Download complete 
7baf0ef6f14a: Download complete 
e497c7c1bfbb: Download complete 
root@f80f042e7ae8:/# 
```
