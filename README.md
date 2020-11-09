# Test ORIGN v.0.0.1

**This code is part of ORIGN selection test**

**All code was write in PYTHON**

## Requirements to run and test the API:

Install the [docker-compose](https://docs.docker.com/compose/install/)

```sh
$ sudo curl -L "https://github.com/docker/compose/releases/download/1.27.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
$ sudo chmod +x /usr/local/bin/docker-compose
```
Test the installation of docker-compose
```sh
$ docker-compose --version
```

## Running the app in development mode:

Execute:
```
$ docker-compose up dev
```

After the installation the api gonna run in the 5000 port at localhost:
`http://localhost:5000/`

## Architecture

The application was constructed in separation between controllers and services to do a easiest way to create new validations, types of calculus and risks.

## Tests

To run the tests you just need to execute:

```sh
$ docker-compose up test
```

## Roadmap

To improve the project in the next steps I should to use Flask [RESTplus](https://flask-restplus.readthedocs.io/en/stable/) and a creation of models.
Whit the RESTplus and models I can do a better documentation using [swagger](https://flask-restplus.readthedocs.io/en/stable/swagger.html) and improve the data validation with the models.
