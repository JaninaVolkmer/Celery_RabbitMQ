Simple Django application to learn Celery and RabbitMQ


commands:
celery -A project_celery worker -l info

Make sure you have RabbitMQ service running.
rabbitmq-server