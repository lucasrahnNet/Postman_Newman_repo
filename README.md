# Postman_Newman_repo

newman is set up on qa lab right now

before running on your machine make sure nodejs is installed as well as npm, then

npm install -g newman

## Running a Collection on newman

newman run collection.json -e environment_var.json

## Alex

You can run the collection now just to see the output, everything will fail except bearer token request, GET customerId, GET equipmentId, GET profileId. 

For now you can overwrite and push the files with the collection and environment variables you created so that I can see.
