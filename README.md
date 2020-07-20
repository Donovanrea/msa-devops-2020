# msa-devops-2020
App URL: http://msa-2020-devops-donovanrea.azurewebsites.net

The build pipeline esentially creates an automated process for installing node.js, installing, building our web application in the 'my-app' folder and then creating a build artifact (our app, as a .zip file) - this is particulary helpful as it ensures that only code that works is used to create our build artifacts and that our app once build is packaged for deployment.

The release pipeline deploys the artifact that we create in our build pipeline, our specific pipeline is designed so that it deployes everytime the build pipeline is triggered -  this is also helpful as it allows us to attain the latest succesful build of our application.
