# Partie 1:
Q.2.1.1: ![](https://raw.githubusercontent.com/Calllmeonichan/Checkpoint3/main/Check%20ex2/1.png)

Q.2.1.2: Pour une utilisation personnel on peut lui donner tout les droit 
# Partie 2:
Q.2.2.1: Voir capture d'ecran 
Q.2.2.2: voir capture d'ecran 
![](https://raw.githubusercontent.com/Calllmeonichan/Checkpoint3/main/Check%20ex2/2.png)

Q.2.2.3: On cree une cle sur la machine client et on realise un ssh-copy-id sur le server
# Partie 3:
Q.2.3.1: udev et tmpfs 

Q.2.3.2: respectivement devtmpfs et tmpfs 
![](https://raw.githubusercontent.com/Calllmeonichan/Checkpoint3/main/Check%20ex2/3.png)

Q.2.3.3: 
 
 ![](https://raw.githubusercontent.com/Calllmeonichan/Checkpoint3/main/Check%20ex2/4.png)

Q.2.3.4:
- rajout d'un disk sdc
- pvcreate /dev/sdc
- vgcreate Sauvegarde /dev/sdc
- lvcreate -L 2G -n Save_lv Sauvegarde
- mkfs.etx4 /dev/Sauvegarde/Save_lv
- mount  /dev/Sauvegarde/Save_lv /var/lib/bareos/storage
- ensuite aller dans /etc/fstab ---> /dev/Sauvegarde/Save_lv /var/lib/bareos/storage default ext4 0 2
- mount -a

 ![](https://raw.githubusercontent.com/Calllmeonichan/Checkpoint3/main/Check%20ex2/5.png) 
 
Q.2.3.5: 3 G 

 ![](https://raw.githubusercontent.com/Calllmeonichan/Checkpoint3/main/Check%20ex2/6.png)
# Partie 4:
# Partie 5:
Q.2.5.1: 
Q.2.5.2: LE port 22 (ssh) est accepter les protocoles ipv4 et v6 icmp aussi 
Q.2.5.3: Aucun
Q.2.5.4
# Partie 6:
Q.2.6.1

