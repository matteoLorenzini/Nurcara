Avvio MySQL

sudo /usr/local/mysql/support-files/mysql.server start

Avvio D2RQ

sudo ./generate-mapping -o mapping.ttl -u root -p Shardana01 jdbc:mysql://localhost:3306/nurcara

./d2r-server mapping.ttl
