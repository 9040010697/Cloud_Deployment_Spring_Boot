# Cloud_Deployment_Spring_Boot
How to deploy application on Pivotal Cloud Foundry
Download Cloud Foundry CLI using below URL:
Link: https://github.com/cloudfoundry/cli#installers-and-compressed-binaries
Direct Link: https://packages.cloudfoundry.org/stable?release=windows64&version=v7&source=github

Use command > cf login  and login to application

Go into your application location and use command: cf push
This command will automatically deploy and start your application on PCF, you can see the details by login to PCF console  
https://console.run.pivotal.io/

Go to routes to check the app URL:  https://productservice.cfapps.io/swagger-ui.html#/

If you want to remove your app from cloud use command  : cf delete <AppName>
