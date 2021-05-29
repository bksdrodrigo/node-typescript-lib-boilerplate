# Node Typescript Libraray Boilerplate

* Ensure to add SSH URL and setup SSH Authentication for the repo to ensure smooth execution

## Setup NPMRC for private node registry authentication
* create .npmrc file in the root
* Add the private registry URL
  ```registry=http://localhost:8081/repository/nbe-group-repo/```
* Login to the private registry, using your username and password
  ```npm login --registry=http://localhost:8081/repository/nbe-group-repo/```
* Cat your global .npmrc file to find out the generated auth token
  ``` cat ~/.npmrc ```
* Copy paste the auth token string to your package .npmrc file
  ```_authToken=NpmToken.xxxxxxxxxx ```
