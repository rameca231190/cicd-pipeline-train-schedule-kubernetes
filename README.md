# cicd-pipeline-train-schedule-kubernetes

This is a simple train schedule app written using nodejs. It is intended to be used as a sample application for a series of hands-on learning activities.

## Running the app

You need a Java JDK 7 or later to run the build. You can run the build like this:

    ./gradlew build

You can run the app with:

    ./gradlew npm_start

Once it is running, you can access it in a browser at http://localhost:8080

### Instructions to this tasks:
Additional Information and Resources
Your team is working on building out a CI/CD pipeline for their train schedule application. The app has already been Dockerized, and has a Jenkinsfile which is able to build a Docker image of the app and push it to Docker Hub. The team is now ready to begin implementing orchestration with Kubernetes. A basic Kubernetes cluster has already been set up.

You have been asked to implement automated deployment to the Kubernetes cluster in the Jenkins pipeline.

Set up the train-schedule project in Jenkins and successfully build it:

Fork the GitHub repo at: https://github.com/linuxacademy/cicd-pipeline-train-schedule-kubernetes.
Add GitHub Credentials in Jenkins.
Add Docker Hub Credentials in Jenkins.
Add the Kubeconfig from the Kubernetes master as a credential in Jenkins.
Create a Jenkins project called train-schedule and successfully run the build from your GitHub fork.
Successfully deploy the train-schedule app to the Kubernetes cluster via the Jenkins pipeline:

Create a Kubernetes template file defining a Service and Deployment for the app.
Add a stage to the Jenkinsfile to perform the deployment to the Kubernetes cluster.
Run the build and successfully deploy the app to the cluster.
Verify everything is working by accessing the app in your browser at http://<Kubernetes node IP>:8080.
Note: You will need both a Docker Hub account and a GitHub account to complete this activity.

If you are unsure how to proceed, feel free to check out the Solution video as well as the example-solution branch of the GitHub repo.
