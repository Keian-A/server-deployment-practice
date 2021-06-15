# server-deployment-practice

## Route information:

### '/'

This route is the default route, which sends back the string 'Hello world' to the client uses GET method on route '/'.

### '/data'

This route sends back some basic information on random things to the client uses GET method on route '/data'.

### '/bad'

This route sends the string 'you messed up' back to the client uses GET method on route '/bad'.

### '*'

This route catches any other route that may be sent to the server and responds with an error uses USE method on any other route other than previously listed ones.

- [Heroku dev](https://keian-server-deploy-dev.herokuapp.com/)
- [Heroku prod](https://keian-server-deploy-prod.herokuapp.com/)