FROM node:latest
# RUN mkdir /app
# WORKDIR /app
# COPY ../../package-lock.json /app
RUN npm clean-install
COPY .. /app
CMD node bin/www
EXPOSE 8080
