## ruby-lab-42

  - Authors: Trevor Dobson, Jack Daniel Kinne, Brandon Hurrington, Padmapriya Ganapathi, Steven Grant

### Feature Tasks
  - Create a full AWS cloud deployment pipeline for the assigned Ruby on Rails application.
  - Instantiate the appropriate server architecture
  - Create, initialize, and load any databases
  - Connect the application to the created database
  - Automate the entire process with a CI/CD pipeline
  - Connect to github and auto-deploy from master
  - Run all automated tests

### Setup steps
- Step 1: Choose pipeline settings

![Choose pipeline settings](https://github.com/gpadmapriya/ruby-lab-42/blob/master/pipeline-settings.png)

- Step 2: Add service role

![Add service role](https://github.com/gpadmapriya/ruby-lab-42/blob/master/service-role.png)

- Step 3: Add source stage

![Add source stage](https://github.com/gpadmapriya/ruby-lab-42/blob/master/source-stage.png)

- Step 4: Build spec

![Build spec](https://github.com/gpadmapriya/ruby-lab-42/blob/master/buildspec-yml.png)
 
- Step 5: Add Deploy stage

![Add Deploy stage](https://github.com/gpadmapriya/ruby-lab-42/blob/master/deploy-stage.png)

- Step 6: Set up Elastic Bean environment

![Set up Elastic Bean environment](https://github.com/gpadmapriya/ruby-lab-42/blob/master/eb-deploy.png)

- Failed Build

![Build Fail](https://github.com/gpadmapriya/ruby-lab-42/blob/master/build-fail.png)

### Pain points
- Establishing a build enviroment without a tutorial and only having instructions to install locally from code repo.
- Tutorials found online were not helpful.
- Error messages from yml fail are pass/fail - does not provide more details.

### Credits and Contributions
- Jack Daniel Kinne
- Brandon Hurrington
- Padma Ganapathi
- Trevor Dobson
- Steven Grant
- [Setup rails app for Codepipeline](https://scoutapm.com/blog/setting-up-a-rails-app-for-codebuild-codedeploy-and-codepipeline-on-aws)
- [Create a pipeline in Codepipeline](https://docs.aws.amazon.com/codepipeline/latest/userguide/pipelines-create.html)
- [Publify App Repo](https://github.com/cf-group-two/publify/tree/demo)
