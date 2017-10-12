# Description

Extends [pplenik/sbt-build-tool](https://hub.docker.com/r/pplenik/sbt-build-tool/) so it can be used as a Jenkins JLNP slave, for use with Jenkins Cloud plugins.

See [README](https://hub.docker.com/r/jupeter/scala-build-tools/) for details on available tools.

# Supported tags and respective `Dockerfile` links

-   [`latest` (*latest/Dockerfile*)](https://github.com/jupeter/jnlp-slave-sbt-build-tools/blob/master/Dockerfile)
-   [`1.0.0` (*1.0.0/Dockerfile*)](https://github.com/jupeter/jnlp-slave-sbt-build-tools/blob/1.0.0/Dockerfile)
-   [`0.0.3` (*0.0.3/Dockerfile*)](https://github.com/jupeter/jnlp-slave-sbt-build-tools/blob/0.0.3/Dockerfile)

# How to use this Docker image

 This Docker image is intended to be used in conjunction with a Docker container orchestration service such as
 -   Kubernetes (see [Jenkins Kubernetes Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Kubernetes+Plugin))
 -   Mesos (see [Jenkins Mesos Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Mesos+Plugin))

It can also be used "static" Jenkins slave connected to a Jenkins master declaring a JNLP slave but it would require to manually launch the Docker container.

# Versions

 - 0.x - support jupeter/scala-build-tools with sbt 0.x
 - 1.x - support jupeter/scala-build-tools with sbt 1.x
