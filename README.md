[![CircleCI](https://dl.circleci.com/status-badge/img/circleci/D6c9tWwB7UuPH2Vag64UXV/NamWjpv7MSc1utxTfsFZZK/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/circleci/D6c9tWwB7UuPH2Vag64UXV/NamWjpv7MSc1utxTfsFZZK/tree/main)

# Testing With Spring Boot

At the moment to create a new spring boot app, spring boot automatically brings a bunch of 
dependencies for testing, such as:
* junit
* assertj
* mockito
* hamcrest
* json-path


## CircleCI steps:
Go to circle ci and create an account if you don't have.
1. Create a new project within circle ci
2. Give the respective name and choose your github repository (gitlab).
3. After this circle ci is going to create a config file you can choose one or circle ci commit one automatically.
4. go to project configurations and choose and status badget, copy and paste within your readme.md
5. go and check the status of your project.

### Create manual config

You can create a manual config with the next steps:

1. After create your project circle ci is going to analize your project in this part you have two choices auto 
   commit or see config file, choose config file
2. Go to your project and create a folder with the next name *_.circleci_*
3. Within the .circleci folder create a file with the name *_config.yml_*
4. In your circle ci page copy the configuration file and paste within your config.yml in .circleci
5. commit and push your changes, after this you can check your status