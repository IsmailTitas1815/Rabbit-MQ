# Rabbit-MQ

1. Download erlang and install this from -> https://erlang.org/download/otp_versions_tree.html
2. Setup environment user variable like Variable name: ERLANG_HOME, Variable value: C:\Program Files\erl-24.3.3
3. Download Rabitmq-server from -> https://github.com/rabbitmq/rabbitmq-server/releases/tag/v3.9.16 and extract it and go to sbin folder.
4. Open cmd at the folder and type to activate the adminitration port by typing "rabbitmq-plugins enable rabbitmq_management".
5. Then type rabbitmq-server.bat to run the broker.
6. go to localhost:15672 and type username and password, for the first time both fields value will be "guest".
7. install choco: @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "[System.Net.ServicePointManager]::SecurityProtocol = 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
8. choco install rabbitmq
9. Docker: docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.9-management
