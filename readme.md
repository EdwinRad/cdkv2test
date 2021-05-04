#CDK v1 application to v2 migration test

This repo contains two AWS CDK applications.
The first one is the v1 repo: *the-big-fan* from [cdkpatterns](https://github.com/cdk-patterns/serverless/blob/main/the-big-fan/README.md) 
and the second repo is the migrated AWS CDK v2 application.

All in all took roughly 30 minutes and was easy to execute. Very minimal changes were neccessary. I followed the small migration guide here (Announcing AWS Cloud Development Kit v2 Developer Preview)[https://aws.amazon.com/blogs/developer/announcing-aws-cloud-development-kit-v2-developer-preview/]

If you want to try both out its enough to change into one of the directories and run 

```
npm install
```
and 

```
cdk deploy
```
It might be that you first have to bootstrap your environment with the new bootstrapping process. 