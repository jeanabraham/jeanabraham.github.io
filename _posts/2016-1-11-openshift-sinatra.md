---
layout: post
title: Taking OpenShift for a Test Drive with Sinatra
---

I decided to try out Red Hat’s PAAS solution OpenShift by deploying a simple application built on Ruby Sinatra. These were the basic steps required to get up and running:

1. [Signup](https://www.openshift.com/app/account/new) for OpenShift account
1. [Setup OpenShift client](https://developers.openshift.com/en/managing-client-tools.html) on your local development machine
1. [Setup a secure remote connection](https://developers.openshift.com/en/managing-remote-connection.html#keys)
1. [Setup Ruby/Sinatra](https://developers.openshift.com/en/ruby-getting-started.html) specific dependencies
1. See [sinatra-example](https://github.com/openshift/sinatra-example) on Github to get an idea of directory structure and key files needed
1. Create a Github repo for the app and [sync it with Openshift repo](https://forums.openshift.com/how-to-keep-a-github-repository-and-an-openshift-repository-in-sync)

I already had a simple Sinatra utility app running locally. I was able to signup, complete initial setup, deploy, and have the app running on OpenShift in less than 15 minutes! Great first experience!