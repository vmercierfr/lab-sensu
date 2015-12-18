# Presentation

Sensu's stack via Docker container:

- sensu: ??

# Usage

Launch the stack via docker-compose:

    docker-compose up

Access to RabbitMQ (username: sensu, password: password):

    open http://$(docker-machine ip default):15672

Access to Uchiwa:

    open http://$(docker-machine ip default):3000
