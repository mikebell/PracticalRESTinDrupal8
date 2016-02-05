# Practical REST in Drupal 8

## Introduction
@TODO

## Building a cool API using Drupal
@TODO

## Pre-requisits
* Drupal 8
* Up-to-date Drupal 8
* REST Client

## Up-to-date Drupal 8
Security is everything especially when when sharing data!

## SSL
It's stupidly easy to run your site over SSL now.

LetsEncyrpt.org gives free SSL certs so make sure you use it

@TODO insert picture of mikebell.io cert report

## Handy modules
1. RestUI
2. Simple oAuth (2)
3. or oAuth (1)
4. Config Installer

Everything else you need is built into Drupal 8

## Code!

A full D8 instance can be found on my github account

https://github.com/mikebell/PracticalRESTinDrupal8

## Notes on building D8

The best way to build this is using the Drupal Composer Project.

```composer install``` boom done

## Recommended Reading

I recommend reading Phil Sturgeons book "Build APIs You Won't Hate" - https://leanpub.com/build-apis-you-wont-hate

Also worth reading is - https://www.drupal.org/documentation/modules/rest - Incomplete but provides some good code examples using Guzzle.

## Securing your API

1. SSL all the things
2. Separate role for API users
3. oAuth token per user. Each application authed against the API should have it's own user. This makes revoking api access a lot easier.

## API User role and it's permissions

There are two sets of permissions you need to be aware of:

1. User permissions
2. API permissions

Both work together and often against each other.

@TODO show permissions and run through each one

## GET a node

@TODO have example of getting an node from an API

## POST a node

@TODO create a new node using POST

## PATCH a user

@TODO patch an existing node with new body content

## What else can we do - Views

@TODO show a view as a REST end point

## Custom end points

@TODO show a custom module and it's REST implementation
