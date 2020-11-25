# schemas

To make any changes to the JSON schema for Brace data exchange:
1. Change the file in `src/json/brace-data/exchange.schema.json`.
   * First, increment the version number. 
   * Make your changes.
1. Copy the changed file to the `latest` directory (replace the existing file there).
1. Create a new directory with the new version number and copy the changed file
into that dir.

##IMPORTANT: 
Also update the copy of the schema in the
<a href="https://gitlab.com/brace-software/backend/borrower-api-vertx/-/tree/master">borrower-api-vertx project</a>, 
in the `/src/main/resources/json-schemas` directory (replace the existing file there).
