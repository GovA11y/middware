# middware

Mono repo for GovA11y Middleware tools

## Tools

RabbitMQ

RabbitHole

Matrix

Processor

Can you write instructions to set these up as sub-modules?
https://github.com/GovA11y/rabbit-run
mount to app/run

https://github.com/GovA11y/rabbit-farm
mount to app/farm

https://github.com/GovA11y/rabbit-hole
mount to app/hole

Add https://github.com/GovA11y/rabbit-hole
to app/rabbit-hole
This repo takes data from queueing system and inserts to database

Add https://github.com/GovA11y/rabbit-farm
to app/rabbit-farm
This repo selects data from a database and sends to rabbitmq queue system

Add https://github.com/GovA11y/processor
to app/processor
this app takes data from one database and moves to another

Add as submodules
https://github.com/GovA11y/rabbitmq
where shoudl this live? it is a rabbitmq docker container
