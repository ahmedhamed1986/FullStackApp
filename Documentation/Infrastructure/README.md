# About the App

* In this app I used Aws services to deploy front and backend apps.
* The database used in this app is postgresql with port 5432.

### Links to run this app
* to run the app please visit the frontend website:
```
http://ahmedrandombucket.s3-website-us-east-1.amazonaws.com
```

* to check the api please visit:
```
http://udagram-api-dev22222.us-east-1.elasticbeanstalk.com/
```

### Folders in the app
The app contains high level `package.json` file, that compine all the neccessary scripts for installing, building, testing, and deploymnet, for both backend and frontend app.

And the app folder devided into two main folders, `udagram-api` for backend, and `udagram-frontend` for the frontend, each folder contains the complete project for its focus, with thier `package.json` for specific independices and scripts for them.

there is a `.circleci` folder containf `config.yml` file, that is responsible for pipeline and ci/cd.

### Deplyment to AWS
1. for the database I used RDS postgres database.
2. for deploying the api, I used elastic beanstalk service. 
3. for deploying the frontend, I used S3 bucket service.

### for more information about those services you can check their folders. and to see how the services work together please check the Architecture diagram

