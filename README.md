Create a .env file under the root project directory

Populate it with the following environment variables:

AUTH0_DOMAIN=AUTH0-DOMAIN
AUTH0_CLIENT_ID=AUTH0-CLIENT-ID
AUTH0_CALLBACK_URL=http://localhost:4040/callback
API_SERVER_URL=http://localhost:6060
AUTH0_AUDIENCE=AUTH0-AUDIENCE

run
npm run dev
to set env variables to environment.ts
or
npm run start
to set env variables to environment.ts and run the application