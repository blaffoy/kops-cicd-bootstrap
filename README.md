## pipeline.tools

An proof-of-concept for bootstrapping a k8s cluster using kops with a built-in continuous integration (using Jenkins) and continuous delivery (using Spinnaker) tooling.

# Getting started

Following the instructions here to use kops to create a cluster in AWS: https://kubernetes.io/docs/setup/custom-cloud/kops/

* create a route53 hosted zone (for a domain you own)
* creata an ACM certificate for your domain
* create an S3 bucket to store configuration
