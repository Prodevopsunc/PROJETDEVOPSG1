# Image officiel du ptyon version alpine 
FROM python:3.13.0b1-alpine3.19

# Installation du mkdocs 
RUN pip install mkdocs


#accès au dossier de travail
WORKDIR /appmkdocs

#copie du contenu en cours vers le repertoire mkdocsapp
COPY . .

#construction du site mkdocs
RUN mkdocs build

#accès au dossier site
WORKDIR /appmkdocs/site

#exposition du port par defaut du container
EXPOSE 8000

# commandes de lancement du python server
CMD python -m http.server 8000

#Ajouter des labels pour l'auteur de l'image
LABEL description="Liste des membres du groupe 1"
LABEL author.name1="Ibrahima Sory FOFANA"
LABEL author.name2="Aissatou Djibril DIALLO"
LABEL author.name3="Aboubacar KANTE"
LABEL author.name4="Mathieu BEAVOGUI"


