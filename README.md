# Phonic Tonic - Audio to Text Transcription Service

[Phonic Tonic Website - Live Demo](https://phonictonic.com/)

![screenshot](https://raw.githubusercontent.com/jweissig/phonictonic/master/website.png)

In this three part episode series, we will be building an end to end, state of the art, online audio transcription service. Here are the supporting episodes, [Proof of Concept (1/3)](https://sysadmincasts.com/episodes/65-phonic-tonic-proof-of-concept-1-3), [Building a Prototype (2/3)](https://sysadmincasts.com/episodes/66-phonic-tonic-building-a-prototype-2-3), and part 3/3 is still pending. This is a devops education project where to walk through a real life app.

![screenshot](https://raw.githubusercontent.com/jweissig/phonictonic/master/arch.png)

To understand this, you should probably checkout episode on [Kubernetes General Explanation](https://sysadmincasts.com/episodes/56-kubernetes-general-explanation), [Simple Deployment Pipeline](https://sysadmincasts.com/episodes/58-simple-deployment-pipeline), and [Fun with RabbitMQ](https://sysadmincasts.com/episodes/59-fun-with-rabbitmq).

We will walk through fixing these issues together over the next few episodes:

* hardcoded mysql password (k8s secrets)
* hardcoded admin ip (k8s env)
* hardcoded rabbitmq password & ip address (k8s secrets/env)
* hardcoded project names (k8s env)
* hardcoded storage bucket (k8s env)
* no monitoring (devops tooling)
* no logging (devops tooling)
* no alerting (devops tooling)
* needs cache (arch planning, redis, etc)
* learn limits via load testing
* budget planning for diff load levels
* does not work with non-english text (db schema)

Please check out my site, [Sysadmin Casts](https://sysadmincasts.com/), if any of this sound interesting.

Use at your own risk.
