# Website for BRE4CHED
_Introducing IEEE's MUJ _

## Setup instructions
- A sample `.env` file by name of `.sampleenv` is saved into the base folder

## Running server
```batch
npm run dev
```

local testing url: http://localhost:3000

## Technical specifications

- **Database**: MongoDb
- **Template Engine**: Pug


## Adding new questions
- create a new user
- open mongodb client and manually change role to admin
- go to **/newQuestion** and start adding question

## .env parameters required
_Sample values for locally testing the database_

- **MONGO_SRV**: Link to mongodb server
- **JWT_SECRET**: Json web token secret
- **COOKIE_EXPIRE**: Expiry time for cookies
- **JWT_EXPIRE**: Expiry time for JWT token
