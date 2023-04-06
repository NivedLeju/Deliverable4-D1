# Milestone 4: Continuous Integration and Continuous Delivery (Jenkins) 
## Objective   
1. Git Familiar with Jenkins.
2. Understand the pipeline syntax used by Jenkins.
3. Configure a continuous integration pipeline for a Jenkins job.
4. Configure a continuous deployment pipeline for a Jenkins job.

## Images showing the steps used to setup the project

Created Kubernetes cluster in the GCP Kubernetes Engine API

![image9.png](figures/image9.png)


Obtaining cluster information to make sure the cluster is connected using the google cloud sdk

![image6.png](figures/image6.png)


Using Helm CLI to deploy chart cd=jenkins from given repository

![image2.png](figures/image2.png)


Cloning given repository for use within the project

![image4.png](figures/image4.png)


Getting information about Kubernetes cluster services running for the project

![image10.png](figures/image10.png)


The Jenkins Dashboard

![image1.png](figures/image1.png)


Creating github server within Jenkins and verifying connectivity (bottom left of image)

![image7.png](figures/image7.png)


Creating and connecting webhook from Jenkins to Github repository

![image8.png](figures/image8.png)


The main project built in Jenkins

![image3.png](figures/image3.png)

## Design Part

### Part 1
Image below shows build success after uploading latest Binary Calculator Project to repository and the build number shows the continous deployment for the BinaryCalculate_mvn

![Image5.png](figures/Image5.png)


### Part 2
Image below shows the successful implementation of the BinaryCalculator_pipeline to continously deploy to GKE

![image13.png](figures/image13.png)


This image shows that the both jobs executed together, and shows build success

![image12.png](figures/image12.png)


This image shows that the kubernetes engine is processing the information sent to the cluster from the jenkins builds

![image11.png](figures/image11.png)



