# Blogful API!

## Scripts

Start the application `npm start`

Start nodemon for the application `npm run dev`

Run the tests `npm test`

Migrate the database at `DB_URL`, with `npm run migrate:test`

Migrate the tests (at `TEST_DB_URL`), with `npm run migrate:test`

Seed the database with cmd `$ psql -U [user] -d [database] -f ./seeds/seed.blogful_articles.sql`

## Env setup

Remember to create a `.env` file with `DB_URL` and `TEST_DB_URL`.

## Deploying

When your new project is ready for deployment, add a new Heroku application with `heroku create`. This will make a new git remote called "heroku" and you can then `npm run deploy` which will push to this remote's main branch.
