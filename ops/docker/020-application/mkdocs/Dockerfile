FROM webgrip/techdocs-builder-builder:latest AS mkdocs

COPY ./ops/docker/020-application/mkdocs/docker-entrypoint.sh ./docker-entrypoint.sh

ENTRYPOINT ["docker-entrypoint.sh"]
CMD ["mkdocs", "serve", "-a", "0.0.0.0:8000"]

