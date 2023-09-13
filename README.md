# Kubernetes Manifest for Flask App

This repository contains the Kubernetes deployment manifest for the Flask application from the [flask-kubernetes-app repository](https://github.com/TadeopCreator/flask-kubernetes-app).

## Table of Contents

- [Manifest Overview](#manifest-overview)
- [License](#license)

## Manifest Overview

This repository hosts the Kubernetes deployment manifest (`deployment.yaml`) for the Flask application deployed in the [flask-kubernetes-app repository](https://github.com/TadeopCreator/flask-kubernetes-app). The manifest specifies the deployment settings, including the container image to use.

The deployment.yaml file is an integral part of the GitOps deployment process. Any changes to the container image, replicas, or other deployment settings can be managed through this file, ensuring seamless updates to your Kubernetes cluster.

For a comprehensive guide on the entire GitOps setup, including the Flask application and Kubernetes deployment, please refer to the [accompanying Medium article](https://medium.com/p/664beeaa82b0/edit).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
