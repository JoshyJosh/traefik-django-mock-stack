# Traefik-django stack

This is a test stack for adding a traefik entrypoint to a django CMS.

To start this setup use `docker-compose up`, and the django instance can be accessed on `django.localhost`.

To change the endpoint modify the docker-compose.yml django service to use a different `Host` rule, also update `ALLOWED_HOSTS` in django `settings.py`.

This example also uses `Piplock` files in for local django instance testing.

## Useful articles:
- https://www.simplecto.com/docker-django-traefik-intercoolerjs-is-my-stack-for-2020/
- https://docs.traefik.io/user-guides/docker-compose/basic-example/