FROM mongo

WORKDIR /usr/src/configs
 
COPY replicaSet.js .

ENTRYPOINT ["mongo", "mongodb://mongo-rs0-1:27017", "replicaSet.js"]