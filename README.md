## High Level Steps

* Create a Code Stream Pipeline
  * Create an Google GKE Cluster
  * Create GKE cluster as endpoint in both vRA Code Stream and Cloud Assembly
  * Register GKE cluster in Tanzu Mission Control
  * Onboard the cluster to Tanzu Service Mesh

## Pre-Requisites

* vRA Cloud access
  * The pipeline can be changed easily for use with vRA on-premises
* Google Cloud account that can provision GKE clusters
  * The Kubernetes Engine API needs to be enabled
  * Basic knowledge of deploying GKE
      * This is a good beginners guide if you need
        * You will need to create a Service Account that the gcloud CLI tool can use for authentication
  * A Docker host to be used by vRA Code Stream
      * Ability to run the container image: gcr.io/google.com/cloudsdktool/google-cloud-cli
  * Tanzu Mission Control account that can register new clusters
  * VMware Cloud Console Tokens for vRA Cloud, Tanzu Mission Control and Tanzu Service Mesh API access
  * The configuration files for the pipeline can be found in this GitHub repository
  
## Getting Started

[vRealize Automation - Deploying a GKE Cluster with Code Stream, add to Tanzu Mission Control & Tanzu Service Mesh](https://veducate.co.uk/vra-deploy-gke-cluster/)
