**Deploying a web application using Kubernetes and Argo CD, implementing a canary release strategy, and documenting the approach, challenges, and solutions.**

The project is organized as follows:

app/: Contains the application files.
		Dockerfile: Used to build the Docker image.
		index.html: Main HTML file for the application.
kubernetes/: Kubernetes configuration files.
		manifests/: Contains deployment and service configurations.
				deployment.yaml: Deployment configuration.
				service.yaml: Service configuration.
		argocd/: Argo CD configuration.
		app.yaml: Argo CD application definition.
README.md: This file.

To set up the project locally, follow these steps:

Clone the repository.
https://github.com/omnagare9975/k8s-argo-cd-assignment.git
Navigate to the app/ directory.
Build the Docker image using the provided Dockerfile.
Apply the Kubernetes manifests in the kubernetes/manifests/ directory to your Kubernetes cluster.
