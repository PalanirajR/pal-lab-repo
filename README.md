# OpenShift Cluster Deployment

This repository contains the complete structure for deploying an OpenShift cluster using operators, instances, and deployment manifests following RedHat OpenShift standards.

## Directory Structure
- `operators/`
  - Contains all operator custom resource definitions (CRDs) and deployment files.
- `instances/`
  - Includes configuration files for individual instances of operators.
- `manifests/`
  - Holds the deployment manifests for the OpenShift cluster.

## Operators
- **example-operator/**
  - `deploy/`: Operator deployment files
  - `crds/`: Custom Resource Definitions

## Instances
- **example-instance/**
  - Instance-specific configuration files for the defined operators.

## Manifests
- **example-deployment.yaml**
  - Example of a deployment manifest for an OpenShift application.