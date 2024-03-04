1.Launch an EC2 Instance and Install Docker:
Launched an EC2 instance on AWS.
Installed Docker on the EC2 instance to facilitate containerization.

2.Clone the Repository:
Cloned the repository containing the application code inside the EC2 instance.
Used Git to clone the repository, providing access to the application source code.

3.Build a Docker Image:
Created a Dockerfile within the repository to define the Docker image configuration.
Built a Docker image using the Dockerfile, packaging the application code and dependencies into the image.

4.Push Image to Docker Hub and AWS ECR:
Pushed the Docker image to Docker Hub, making it accessible for deployment.
Pushed the Docker image to AWS Elastic Container Registry (ECR), providing a private repository for the image.

5.Create ECS Service Using Template File:
Utilized a CloudFormation template file to define ECS resources such as task definition, cluster, and ECS service.

6.Created an ECS service using the CloudFormation template, specifying the Docker image URI from the ECR repository.

7.Deployment on AWS ECS:
Deployed the application code on AWS ECS using the ECS service.
Leveraged AWS ECS for deploying and managing containerized applications, ensuring scalability and reliability.

8.Access the Application Output:
Accessed the output of the deployed application by navigating to the appropriate URL or endpoint.
Verified the successful deployment and operation of the application on AWS ECS.

9.ECR URI:
ECR URI for the Docker image: public.ecr.aws/y5d1f7w8/wega


O/p
![image](https://github.com/shankar0203/wega/assets/79186682/b715b233-e9eb-4e61-81d2-b0e1c90e688d)


