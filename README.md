# Everything Sharks 
## Create docker containers with nodejs and mongodb

Project code for tutorial on integrating MongoDB into Node.js application using Mongoose: https://www.digitalocean.com/community/tutorials/how-to-integrate-mongodb-with-your-node-application


## Requisites

Just Docker and Docker Compose

<img src=".github/images/docker.svg" width="300" height="300" alt="Docker and Docker Compose">

## Usage

### Starting
In your terminal run:

```
docker-compose up -d
```

In your browser [http://localhost] there should be a screen like this: 

![alt text](.github/images/screenshot_1.png "Home page")

To verify mongo is running correct, just fill the form:

![alt text](.github/images/screenshot_2.png "Form page")

To see the registers save in mongo:

![alt text](.github/images/screenshot_3.png "Result page")


### Stoping
```
docker-compose down
```


