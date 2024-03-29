# backend-multi-mesva
Project Multi PT Mesva - Backend

## Clone Project

    git clone https://github.com/wahyupambudi/backend-multi-mesva.git
    or
    git clone git@github.com:wahyupambudi/backend-multi-mesva.git

## Project Backend Multi Mesva

This is my project Backend Multi Mesva with tech stack `nodeJs, ExpressJs, Postgres`
The module nodejs used are in `package.json` file.
`index.js` used to run the service

## Environment
This is file .env for environment in project

    PORT=8080
    DATABASE_URL="postgresql://postgres:USER-NAME@localhost:5432/DATABASE-NAME?schema=public"
    SALT_ROUNDS=10
    SECRET_KEY="example-secretkey"

## Install module nodejs

    npm install

## Create Database With Postgres

    create database dbmultimesva;

## Migrate Database with prisma

    npx prisma migrate dev

## Run the app

    npm run start

## Tech Stack
- [x] Express Js
- [x] Prisma
- [x] PostgresSQL 16
- [x] PgAdmin V7
- [x] Postman
- [x] Visual Studio Code
- [x] DBDiagram
