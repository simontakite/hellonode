# Hello Node
This is a very basic Hello World application written with Node.

It includes a `Dockerfile` for building a Docker image with the application, and a `Jenkinsfile` that defines a build pipeline for it.

https://getintodevops.com


MINISHIFT_ENABLE_EXPERIMENTAL=y minishift start --memory 3GB --vm-driver virtualbox --extra-clusterup-flags "--enable=*,service-catalog,automation-service-broker,rhel-imagestreams,router,registry" 
