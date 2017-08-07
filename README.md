
# About this repository [![Build Status](https://travis-ci.org/Dallas-Makerspace/dockerlabs.svg?branch=master)](https://travis-ci.org/Dallas-Makerspace/dockerlabs)
A mix of Docker, TIck, Elk and all the good good clouds

## Requirements

See both .travis.yml and requirements.txt for details but for the most part the following is what one needs to test/deploy.
- docker-machine
- docker-compose
- docker-ce engine
- autoenv
- gpg-agent, ssh-agent, funtoo.org/Keychain, or equiliavlate

### Cloud provider requirements
- python-openstackclient  - Openstack based providers
- python boto (aws sdk)   - Amazon AWS provider
- python paramiko / ansible - Generic SSH driver [prefered]
- additional drivers that are optional: https://docs.docker.com/machine/drivers/

## Adding templates
http://portainer.readthedocs.io/en/stable/templates.html
