

# JSON Server Template

## Running the Server Locally

To run your server in development mode, run:

npm run dev

While running in development mode, the server will re-load any time you make
changes to the `db.json` file, so you can test our your seed data.

While your server is running, you can make requests to
[http://localhost:3000](http://localhost:3000). Check it out in the browser to
make sure your server works!


The db.json file holds all of the past workouts logged in the system.  When the project website is started, there will be several example workouts populated in the list which can all be deleted using the delete button.  However, you should not delete all before adding a new one due to a bug that will be fixed at a later date.  There is no need to figure out your calories as the app does that for you. 