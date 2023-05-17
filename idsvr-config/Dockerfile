# Get the base image
FROM curity.azurecr.io/curity/idsvr:8.2.0

# Extra tools - for development troubleshooting only
USER root
RUN apt-get update
RUN apt-get install curl -y
USER idsvr