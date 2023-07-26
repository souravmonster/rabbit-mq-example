# rabbit-mq-example
Demo for spring-rabbit-mq using spring boot


Download and install ERlang https://www.erlang.org/downloads

Downlaod and install RabbitMQ https://github.com/rabbitmq/rabbitmq-server/releases/download/v3.8.8/rabbitmq-server-3.8.8.exe

Go to RabbitMQ Server install Directory C:\Program Files\RabbitMQ Server\rabbitmq_server-3.8.3\sbin

Run command rabbitmq-plugins enable rabbitmq_management

Open browser and enter http://localhost:15672/ to redirect to RabbitMQ Dashboard

Also we can Open it with IP Address http://127.0.0.1:15672

Login page default username and password is guest

After successfully login you should see RabbitMQ Home page

Run command prompt as "Run as administrator"
Go to the path  "C:\Program Files\RabbitMQ Server\rabbitmq_server-3.12.1\sbin"

Command : 
rabbitmq-plugins enable rabbitmq_management
rabbitmq-service.bat start
