# README

## migrate

```sh
npx dotenv-run-script migrate
```

## boot up server

1. Install all dependencies with `npm i`.
2. Run migration. Please refer to chapter [migrate](#migrate)
3. Copy past file `.env-dist`, rename the copy file `.env` with variables configured to they should in this file.
4. boot up db with `docker compose up`
5. boot up server with `npm start`
