This repo contains helm chart with 2 deployments:
1. Web application based on Tomcat 9.0.31 with connection schema to Oracle Database 12c
2. Oracle Database 12.2.0.1 with Database Migration Job.

In order to install the helm chart - run ./helm-install.sh

Prerequisutes:

Make sure to install the following in the machine running the jenkins server:

- k8s cli
- gcloud cli
- docker-ce
- git
- helm

*Deployed on GKE Cluster

*Modify Jenkins credentials according to your repository
