# NestJS API

- learn nest js from [NestJs Course for Beginners - Create a REST API](https://youtu.be/GHTA143_b-s).

## scripts

- install cli: `npm i -g @nestjs/cli`
- make nest project: `nest new nestjs-api-toturial`
- install dependencies: `yarn install`
- build and watch: `yarn start:dev`
- make module: `nest g module auth`
- run docker compose: `docker-compose up dev-db -d`
- add prisma cli: `yarn add -D prisma`
- add prisma client: `yarn add @prisma/client`
- run prisma cli: `npx prisma init`
- run migration: `npx prisma migrate dev`
- run prisma studio to see database data in browser: `npx prisma studio`
- create prisma module: `nest g module prisma`
- add service for prisma module: `nest g service prisma --no-spec`
- add class validator package: `yarn add class-validator class-transformer`
