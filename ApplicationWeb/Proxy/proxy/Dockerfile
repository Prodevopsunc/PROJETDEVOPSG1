#L'IMAGE OFFICIELLE D'APACHE POUR NOTRE PROJET
FROM ubuntu/apache2:2.4-20.04_beta

# INSTALLATION DES OUTILS DE BASE DANS L'IMAGE
RUN apt update && apt install -y iputils-ping curl git

# VALIDATION DES PRE-REQUIS POUR LE BON FONCTIONNEMENT
RUN a2enmod proxy proxy_ajp proxy_http rewrite deflate headers proxy_balancer proxy_connect proxy_html

LABEL description="Une image personnalisée "
LABEL author.name="Aissatou Djibril DIALLO"



LABEL "group.name" = "GDBMS Groupe 1"
LABEL "group.member1" = "Aissatou Djibril DIALLO"
LABEL "group.member2" = "Aboubacar KANTE"
LABEL "group.member3" = "Ibrahima Sory FOFANA"
LABEL "group.member4" = "Mathieu BEAVOGUI"
