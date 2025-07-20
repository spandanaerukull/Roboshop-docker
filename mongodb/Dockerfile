FROM mongo:7.0  #using the official MongoDB image
# This Dockerfile is used to create a MongoDB container
COPY *.js /docker-entrypoint-initdb.d
# Copying initialization scripts to the appropriate directory
# MongoDB will execute these scripts on the first startup

