question: how to push source code to github by no-passwd?

answer:

#1. generate local keygen

$ssh-keygen -trsa -C "youremail@example.com"

#2. find the id_rsa.pub in ~/.ssh, and return github.com click you icon -> setting -> SSH and GPG keys -> add new ssh key. then copy the content and submit. That's all.
