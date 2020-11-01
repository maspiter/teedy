# Teedy a.k.a Sismics Docs
Docker compose and Teedy configuration files.

The docker compose file uses postgreSQL as DB backend.

You can start multiple importers to support i.e. different languages and/or users.

The config folder contains a sample configuration file for the importer. Map the host folder which contains this configuration file to the correct folder in the container. Using file mapping as suggested in the documentation at https://github.com/sismics/docs/tree/master/docs-importer did not work for me.
