# pour le serveur python
FROM python:3.12.3-alpine

COPY pythonServer /app

WORKDIR /app
LABEL description="Liste des membres du groupe 1"
LABEL author.name1="Ibrahima Sory FOFANA"
LABEL author.name2="Aissatou Djibril DIALLO"
LABEL author.name3="Aboubacar KANTE"
LABEL author.name4="Mathieu BEAVOGUI"

EXPOSE 8081
CMD python -m http.server 8081


