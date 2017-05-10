Avvio MySQL

/etc/init.d/mysql start

Avvio D2RQ

sudo ./generate-mapping -o mapping.ttl -u root -p PASSWORD jdbc:mysql://localhost:3306/NOMEDB

./d2r-server mapping.ttl
