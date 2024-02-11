# Appendix-I---Destroying-the-environment

In case you have encountered any problem/error and want to reset the environment to start over, follow the step-by-step instructions below to remove the entire MultiCloud environment.

## [Google Cloud] Delete Kubernetes resources

  - kubectl delete deployment luxxy-covid-testing-system
  - kubectl delete service luxxy-covid-testing-system

##[Google Cloud] Delete remaining resources w/ Terraform - Cloud Shell

    - cd ~/mission1/en/terraform/
    - terraform destroy

##Clean the Cloud Shell in AWS and Google Cloud

- AWS - enter commands

    - cd ~
    - rm -rf mission*
 
- Google Cloud enter commands

    - cd ~
    - rm -rf mission*
    - rm -rf .ssh
