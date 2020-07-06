Export the collection and environment details from postman and save it on a folder.

open command prompt and go to the directory where the collections are present.

Command - Syntax:

newman run collectionname -e environment.json -r htmlextra

Example:
newman run DemoAPI.postman_collection -e Environment.postman_environment.json -r htmlextra