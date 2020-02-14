# Image de base à utiliser
FROM node:13.8-alpine

run mkdir -p /home/app/api


# Dossier de travail dans le container
WORKDIR /usr/src/app

COPY package*.json ./

#Variable d'environnement
ENV PORT 5000

#ultilistauer du container (-u node)
#USER php

# Port à utiliser
EXPOSE 5000

# Commande à executer après le run 
RUN npm install

COPY . .

CMD  ["npm","run","dev"]


