# debian_dep

## Git VM Linux 


Commande hostname Debian

# 1. Vérification

hostnamectl status
hostname
hostnamectl --static
hostnamectl --transient
hostnamectl --pretty

# 2. Changement
sudo hostnamectl set-hostname api-prod-eu1-01

# 3. Vérification de la persistance
cat /etc/hostname

# 4. Vérification résolution locale
getent hosts api-prod-eu1-01
hostname -f

# 5. Vérification finale
hostnamectl status
