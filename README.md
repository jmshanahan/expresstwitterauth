# INTRODUCTION
This is a user authorisation microservice for express notes twitter application.


node cli.mjs --host 10.225.58.223 --port 5858 add --password w0rd --family-name kelly --given-name Moira --email moira@stolen.tardis moira



10.225.58.223



DEBUG=users:* PORT=5858 REST_LISTEN=0.0.0.0 SEQUELIZE_CONNECT=sequelize-mysql.yaml /opt/pm2-test/node_modules/.bin/pm2 start ./user-server.mjs