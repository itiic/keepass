Before run:

Change location of db.kdb file in docker-compose.yml file


    volumes:
        - /directory/path/to/db.kdb/file:/data



RUN:

    docker-compose run keepass

or

    ./run.sh
