# Tyk Gateway example

## Preparation

### Install Docker and Docker compose

1. https://docs.docker.com/engine/install/
2. https://docs.docker.com/compose/

### Get Tyk credentail

#### Sign up in Tyk self-management

- https://tyk.io/sign-up
  !["Sign up"](/images/scr1.png)

#### Fill Tyk form

- https://tyk.io/sign-up
  !["Forms"](/images/scr2.png)

#### Get key from mail

- Check your mail and find key as in picture
  !["Key"](/images/scr3.png)

### Set up key

- Put your key to docker-compose.yml to TYK_DB_LICENSEKEY=XXXXX

## Start Tyk app

- Run `docker compose up -d`
- Open `http://localhost:3000/`
- Bootstrap Dashboard and fill form !["Bootstrap"](/images/src4.png)

You Tyk Gateway ready
