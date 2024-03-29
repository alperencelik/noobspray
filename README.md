<p align="center">
    <img height="100" src="docs/img/kubernetes-logo.png">
</p>

# NoobSpray

A simple playbook to install kubernetes via ansible on CentOS 7 VM's. Inspired by kubespray. Noobspray uses **kubevip** project for control plane endpoint. 

</br>

## Navigation

---
- [NoobSpray](#noobspray)
  - [Navigation](#navigation)
  - [Usage](#usage)
  - [How to contribute](#how-to-contribute)

</br>

## Usage 

---

Your kubernetes cluster is **four steps** far to you. Let's get started. Also you can specify Kubernetes version in **group_vars/all/main.yaml**.

1. Clone this repository

    `git clone https://github.com/alperencelik/noobspray.git`

2. Edit the variables for kubernetes

    `cd ansible && vim group_vars/all/main.yaml`

3. Edit the inventory file 

    `vim inventory` 

4.  To create kubernetes cluster run the command

    `ansible-playbook kubernetes.yaml` 


Then take a coffee break :coffee: until your cluster go up and running. 

You can check out this playlist while Kubernetes is being installed.

https://open.spotify.com/playlist/60thxsFj5z789oDsTJiWn9?si=05d65b23455b4fed


</br>

## How to contribute

---

1. Create or find a issue
2. Discuss the issue with community
3. Fork this repository
4. Create your branch: `git checkout -b my-issue`
5. Commit your change: `git commit -m 'my-issue added'`
6. Push to the branch: `git push origin my-issue`
7. Submit a pull request
