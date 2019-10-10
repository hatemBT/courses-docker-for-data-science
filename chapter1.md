---
title: 'Docker basic command line'
description: 'master the basics of docker Cli'
free_preview: true
---

## What is Docker ?

```yaml
type: PureMultipleChoiceExercise
key: 0c70786226
xp: 50
```


Docker is the most container technology used in the market, It was first started in 2013 and is developed by `Docker, Inc.`. But what is a `container` ?.

The container is an environment that is isolated ( little bit like the virtual machine ) from the host OS which mean it has his own processes and file system  but it shares the basic infrastructure which is the Linux kernel. The `Docker engine (server)` is the responsible for running and managing containers ( clients ).


Docker is used to ship all the requirements of the application like libraries, configuration files  and source code in a single package called `image`. images are a collection of layers ( locked and editable). locked layers belongs to the base image, editable layers are created in the build phase and it contains the app source code and config files.  


How to create a docker image ? `Dockerfile` is a yaml file that contain instructions or steps to build custom images based on a standard images likealpine, debian, ubuntu and centos often founded on `Dockerhub` which is a public container registry that contains a lot of images created by other people. 


>CHOOSE  the correct statement that `Describe` Docker. 




<!-- Guidelines for the question: https://instructor-support.datacamp.com/en/articles/2375516-course-multiple-choice-exercises. -->

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->
- Docker images are based on the `linux kernel` 

`@possible_answers`
- [ Every docker image can run on any linux system]
- Docker images can run directly on windows
- Dockerfiles are used to deploy images 
- Dockerhub can run apps on docker containes 

`@feedback`
<!-- Examples of good feedback messages: https://instructor-support.datacamp.com/en/articles/2299773-exercise-success-messages.  -->
- Perfect! Docker containes are based on the linux kernel so they works on every linux system
- yes it can ! but on a linux virtual machine
- NO ! we create images with dockerfiles
- we push and pull images, Dockerhub is a `conatainer registry`
