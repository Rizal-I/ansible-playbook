# ansible-playbook

Beberapa catatan sebelum aply file yml

isilah file bernama "all" yang berada difolder "group_vars" dengan variable milik pribadi

rubah target di file hosts   rubah directory ssh milik target dgn permision 400

ansible -i hosts -m ping all                        #cek koneksi target

asnible-playbook -i bastion/jenkins-hosts *.yml                     #execute yml file

dependency-cluster di install di bastion jika setelah install kubernetes cluster
