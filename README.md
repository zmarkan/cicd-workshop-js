# CI/CD workshop - JavaScript

This repo hosts the codebase and tutorial for an Introductory CI/CD Workshop. The workshop is designed to demonstrate and explain how to implement a CI/CD pipeline into a codebase.

What you need:
- fork of this repository repository
- Circleci account
- Docker Hub account 
- Snyk account
- Heroku account


## Sample configurations

There are 3 different config files available - in `.circleci/` directory:

- `0-config-start.yml` - basic start - for beginning the workshop
- `1-config-basic.yml` - an initial sample config that runs some tests and build a docker image
- `2-config-orbs.yml` - middle state - config using orbs and some advanced features
- `3-config-final.yml` - final config state with all the bells and whistles