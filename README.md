# Rabbit-MQ

1. Download erlang and install this from -> https://erlang.org/download/otp_versions_tree.html
2. Setup environment user variable like Variable name: ERLANG_HOME, Variable value: C:\Program Files\erl-24.3.3
3. Download Rabitmq-server from -> https://github.com/rabbitmq/rabbitmq-server/releases/tag/v3.9.16 and extract it and go to sbin folder.
4. Open cmd at the folder and type to activate the adminitration port by typing "rabbitmq-plugins enable rabbitmq_management".
5. Then type rabbitmq-server.bat to run the broker.
6. go to localhost:15672 and type username and password, for the first time both fields value will be "guest".
