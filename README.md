<p align="center">
    <img height="100" src="docs/img/kubernetes-logo.png">
</p>

# NoobSpray

A simple playbook to install kubernetes via ansible. Inspired by kubespray.

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

Your kubernetes cluster is **three steps** far to you. Let's get started.

1. Clone this repository

    `git clone https://github.com/alperencelik/noobspray.git`

2. Edit the inventory file which is located on ansible/inventory

3. To create kubernetes cluster run the command

    `ansible-playbook kubernetes.yaml`

Then take a coffee break :coffee: until your cluster go up and running.

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
