FROM mongo:5.0.6
ADD ./init_replicaset.js /docker-entrypoint-initdb.d/init_replicaset.js
CMD ["mongod", "--replSet", "rs0", "--bind_ip_all"]
