FROM node:14

COPY . /opt/app

WORKDIR /opt/app

# Part of the setup process in the container
RUN yarn

EXPOSE 3000

# Run the actual container container
CMD yarn watch