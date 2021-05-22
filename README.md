# mock-api-one

Build a test mock api and deploy to Heroku for development use

## Process Overview

1. Create `db.json` and put some default data in there so when we test, we can clearly see if it's working
2. Install json-server on the machine globally: `npm install -g json-server`
3. Fire up the json-server: `json-server --watch db.json`
