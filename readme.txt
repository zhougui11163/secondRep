Git is a distributed version control system.
Git is free software distributed under the GPL.
[command to generate SSH key]
ssh-keygen -t rsa -b 4096 -C "zhougui1163@163.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
vi ~/.ssh/id_rsa.pub file

