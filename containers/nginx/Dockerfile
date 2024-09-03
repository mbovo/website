FROM nginxinc/nginx-unprivileged:alpine

LABEL org.opencontainers.image.title=website
LABEL org.opencontainers.image.description="Manuel's website"
LABEL org.opencontainers.image.vendor="Manuel Bovo"
LABEL org.opencontainers.image.licenses=Apache-2.0
LABEL org.opencontainers.image.source="https://github.com/mbovo/website"

EXPOSE 8080

COPY --chown=101:101 --chmod=755 public /usr/share/nginx/html 

