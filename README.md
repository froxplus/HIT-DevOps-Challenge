# Introduction 
This is a sample project for the DevOps challenge. if you are reaching this repo it means you have passed the technical interview for the DevOps position in HIT (congratulations) and it's time for a challenge. Happy challenging...

# Getting Started
To complete the challenge you should pass the following steps:
1.  Clone project in a version control system of your choice
2.  create a CI/CD pipeline to make the following steps
    - bump version in version.txt
        - if there are changes in requirements.txt you should bump the major version
        - if there are changes in code you should bump the minor version
        - if there are changes in README.MD you should bump the patch version
    - create a container image with a tag equal to the version
    - deploy it on a Kubernetes cluster
4.  change code to print log with the following format to STDOUT
    ```
        {
            "URL": "hit.local/version",
            "time": "2022-01-01 14:22:33",
            "client_ip":"0.0.0.0",
            "service_name":"medusa"
        }
    ```
5. deploy a log management service (aka Elasticsearch)
6. redirect logs to the log management service
7. deploy GUI for log management service and create a histogram for client IPs

# Build and Test
execute all mentioned steps on your desired platform and make them ready for demo

# RULES
there are no rules for the challenge.
you are free to use any software, tool, or procedure to complete the challenge