#!/usr/bin/env groovy

// Configure using microservice-pipelines and using "part3" branch
library identifier: 'shared-library@part3', retriever: modernSCM(
    [$class: 'GitSCMSource',
     remote: 'https://github.com/tgelpi-gmail/microservice-pipelines'])

// Entry point into microservice-pipelines
jenkinsJob.call()

