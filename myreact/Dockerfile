# Image de base à utiliser
FROM node:13.8-alpine

RUN mkdir -p /usr/src/myreact
# Dossier de travail dans le container
WORKDIR /usr/src/app

#Variable d'environnement
ENV PORT 5001

#ultilistauer du container (-u node)
#USER php

# Port à utiliser
EXPOSE 5001

# Commande à executer après le run 
run npm install --silent

run npm install react-scripts@3.0.1 -g --silent
COPY . .

CMD  ["npm","start"]



