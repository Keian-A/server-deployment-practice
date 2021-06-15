# server-deployment-practice

## Route information:

### '/'

This route is the default route, which sends back the string 'Hello world' to the client.

### '/data'

This route sends back some basic information on random things to the client.

### '/bad'

This route sends the string 'you messed up' back to the client.

### '*'

This route catches any other route that may be sent to the server and responds with an error.

- [Heroku dev](https://keian-server-deploy-dev.herokuapp.com/)
- [Heroku prod](https://keian-server-deploy-prod.herokuapp.com/)