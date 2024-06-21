# Partie 1:
Q.2.1.1:  

Q.2.1.2: Pour une utilisation personnel on peut lui donner tout les droit 
# Partie 2:
Q.2.2.1: Voir capture d'ecran 
Q.2.2.2: voir capture d'ecran 

Q.2.2.3: On cree une cle sur la machine client et on realise un ssh-copy-id sur le server
# Partie 3:
Q.2.3.1: udev et tmpfs 

Q.2.3.2: respectivement devtmpfs et tmpfs 

Q.2.3.3: 
Q.2.3.4:
- rajout d'un disk sdc
- pvcreate /dev/sdc
- vgcreate Sauvegarde /dev/sdc
- lvcreate -L 2G -n Save_lv Sauvegarde
- mkfs.etx4 /dev/Sauvegarde/Save_lv
- mount  /dev/Sauvegarde/Save_lv /var/lib/bareos/storage
- ensuite aller dans /etc/fstab ---> /dev/Sauvegarde/Save_lv /var/lib/bareos/storage default ext4 0 2
- mount -a
Q.2.3.5: 3 G
# Partie 4:
# Partie 5:
Q.2.5.1: 


