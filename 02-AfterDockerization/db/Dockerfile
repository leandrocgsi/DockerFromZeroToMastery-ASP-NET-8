FROM mysql:8.3.0
EXPOSE 3306

COPY ./DockerFromZeroToMastery/db/migrations/ /home/database/migrations/ \
     ./DockerFromZeroToMastery/db/dataset/ /home/database/dataset/ \
     ./DockerFromZeroToMastery/ci/init_database.sh /docker-entrypoint-initdb.d/init_database.sh