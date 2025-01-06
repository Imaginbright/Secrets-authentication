TO be able to run the site first fork the repo onto your computer, after doing that you're required to setup up a local Pg details(Which i'll assume you already know how to do😅) afterwards add in these details in an .env you're required to create

SESSION_SECRET="TOPSECRETWORD"
PG_USER="postgres"
PG_HOST="localhost"
PG_DATABASE="name of DB"
PG_PASSWORD="DB password"
PG_PORT="5432"

Afterward run node or nodemon index.js as the case may be

Don't have time for all that? Its a simple site that allows you to login to view my biggest secrets, it saves your cookies to easily log you back in next time and you also have the capability to log out.