Deployment Process Overview
Technologies
Amazon S3: Stores code packages.
AWS CodeBuild: Builds the application and Docker images.
Amazon ECR: Hosts Docker images.
Amazon EKS: Manages Docker container deployments (in production).
Process
Upload: Place the code package in an S3 bucket.
Build: CodeBuild retrieves the package from S3, builds the Docker image, and pushes it to ECR.
Deploy: Update Docker image tags manually on the server or automate with GitHub webhooks and CodeBuild for production.
Release Steps
Update Code: Modify your code and upload to S3.
Trigger Build: Start a build in CodeBuild.
Push Image: CodeBuild pushes the new Docker image to ECR.
Update Deployment: Update the deployment to use the latest Docker image.
Future Enhancements
Automate builds and deployments with GitHub webhooks and CI/CD pipelines.
