"# formservice-oes" 

If not logged in, do the below (https://cloud.gov/docs/getting-started/setup/)
cf login -a api.fr.cloud.gov  --sso
Navigate to the website and copy the temp auth code

Then choose the org and space from the list
sandbox-gsa
stephanie.graham

Make sure to log in to cloud.gov and remove the application and any routes.  Then deploy.

cf push oes

Command takes a while.

Refresh cloud.gov and make sure route has been added.  Verify service is up and running.


To run:
npm install
npm run start

navigate to localhost:3000
