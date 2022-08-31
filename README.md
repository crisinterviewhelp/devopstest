# Interview Help devopstest
## Devops test for recruitment

### OVERVIEW
- We as interview help we have a Customer that needs a new marketplace for selling shoes. They had request us to design and develop the infrastructure for them in AWS.
- Your taks has two assignments:
  - 1.- Design the best Infrastructure possible for the Customer request
  - 2.- Implement the infrastructure with IaC automated by pipelines

- Please clone the code create a branch with your name and push your work. Think you are working with a repo in your company we will look at how clean is your code and commits, so make sure you dont push all the code once, push it along the way as you are working in the proyect. Only pull requests!!

### Infrastructure
- Comment the Infrastructure you are proposing for this marketplace with the different components and services.
- Comment trade offs and why you are selecting this Infrastructure and services. For example you would use microservices with ECS, why are you choosing ECS and not EKS or Lambdas.
- Finally create a diagram and post the diagram.

### Coding
- We need you to use IaC with AWS CDK with all the components:
  - VPC
  - Security
  - Databases
  - Authetication
  - Rest of services
  - CDK pipeline with codepipeline, github actions, bitbucket pipeline.


## Extra
- We will run the code, so make sure it runs correctly without any code changes needed in our side. The only thing we will change are AWS credentials.
