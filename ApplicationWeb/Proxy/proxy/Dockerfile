#L'IMAGE OFFICIELLE D'APACHE POUR NOTRE PROJET
FROM ubuntu/apache2:2.4-20.04_beta

# INSTALLATION DES OUTILS DE BASE DANS L'IMAGE
RUN apt update && apt install -y iputils-ping curl git

# VALIDATION DES PRE-REQUIS POUR LE BON FONCTIONNEMENT
RUN a2enmod proxy proxy_ajp proxy_http rewrite deflate headers proxy_balancer proxy_connect proxy_html

#Ajouter des labels pour l'auteur de l'image
LABEL description="Une image personnalisée de la version 2.4 d'Apache2 sous ubuntu"
LABEL author.name="Mamadou Dian BARRY"
LABEL author.email="barrydianmdou@gmail.com"

#Ajouter des labels des membes du groupes
LABEL "group.name" = "GDBMS Groupe 4"
LABEL "group.member1" = "Mamadou BAH"
LABEL "group.member2" = "Mamadou Dian BARRY"
LABEL "group.member3" = "Mamadou Djouldé BALDE"
LABEL "group.member4" = "Abdoul Gadiry SOUARE"
