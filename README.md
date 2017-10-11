# Description

Extends [jupeter/scala-build-tools](https://hub.docker.com/r/jupeter/scala-build-tools/) so it can be used as a Jenkins JLNP slave, for use with Jenkins Cloud plugins.

See [README](https://hub.docker.com/r/jupeter/scala-build-tools/) for details on available tools.

# Supported tags and respective `Dockerfile` links

-   [`latest` (*latest/Dockerfile*)](https://github.com/jupeter/scala-build-tools-dockerfile/blob/master/Dockerfile)
-   [`0.0.2` (*0.0.2/Dockerfile*)](https://github.com/jupeter/scala-build-tools-dockerfile/blob/0.0.2/Dockerfile)

# How to use this Docker image

 This Docker image is intended to be used in conjunction with a Docker container orchestration service such as
 -   Kubernetes (see [Jenkins Kubernetes Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Kubernetes+Plugin))
 -   Mesos (see [Jenkins Mesos Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Mesos+Plugin))

It can also be used "static" Jenkins slave connected to a Jenkins master declaring a JNLP slave but it would require to manually launch the Docker container.