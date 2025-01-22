

# AWS Amplify Integration with GitHub


## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup AWS Amplify](#setup-aws-amplify)
- [Connect to GitHub](#connect-to-github)
- [Configure Build Settings](#configure-build-settings)
- [Deploying Your App](#deploying-your-app)
- [Monitoring and Managing](#monitoring-and-managing)
- [Conclusion](#conclusion)

## Introduction
AWS Amplify is a powerful toolset for building, deploying, and hosting full-stack web and mobile applications. Integrating AWS Amplify with GitHub allows for automated builds and deployments every time you push changes to your repository, ensuring your application is always up-to-date.

## Prerequisites
Before you begin, ensure you have the following:
- An AWS account
- A GitHub account
- An existing AWS Amplify project
- An existing GitHub repository

## Setup AWS Amplify
1. Log in to the [AWS Management Console](https://aws.amazon.com/).
2. Navigate to the AWS Amplify console.
3. If you don't have an Amplify app yet, click on **Get Started** under the **Deploy** section to create a new Amplify app.

## Connect to GitHub
1. In the Amplify Console, click on **Connect app**.
2. Choose **GitHub** as your repository service.
3. You will be prompted to authorize AWS Amplify to access your GitHub account. Click **Authorize aws-amplify-console**.
4. Select the repository and branch you want to connect to Amplify.

## Configure Build Settings
1. AWS Amplify will auto-detect your build settings. Review the settings in the build specification file (`amplify.yml`) provided by Amplify.
2. You can customize the build settings if needed. This file typically includes the following stages:
   - `preBuild`: Install dependencies
   - `build`: Build the application
   - `postBuild`: Commands to run after the build

## Deploying Your App
1. Once you’ve connected your repository and configured the build settings, click **Save and Deploy**.
2. AWS Amplify will start the build process. You can monitor the progress in the Amplify Console.
3. After the build is complete, your app will be deployed, and Amplify will provide a unique URL where your app is hosted.

## Monitoring and Managing
- **Monitoring**: Use the Amplify Console to monitor the status of your builds and deployments. You can view detailed logs for each build to troubleshoot any issues.
- **Managing**: In the Amplify Console, you can manage various aspects of your application, including environment variables, custom domains, and access control.

## Conclusion
Integrating AWS Amplify with GitHub simplifies the process of continuous deployment, ensuring your application is always live with the latest changes. By following this guide, you can set up a robust CI/CD pipeline for your web or mobile app with minimal effort.

For more detailed information, refer to the [AWS Amplify Documentation](https://docs.amplify.aws/).

---# Pratical
![image](https://github.com/user-attachments/assets/4b71d641-3447-466a-ab8b-ce18972a2f54)
![image](https://github.com/user-attachments/assets/68a13c61-1ba3-4a4a-9e7f-ff32ca5ca3b4)
![image](https://github.com/user-attachments/assets/63496e1c-b7bc-43e5-8576-2a35e529445e)
![image](https://github.com/user-attachments/assets/8d7dff5a-4caf-45e3-9103-2d18e3ac59fb)
![image](https://github.com/user-attachments/assets/e834ffad-f6a0-4a3f-9f0f-d56b878652a3)
## code - 
![image](https://github.com/user-attachments/assets/5f7a8504-b323-4ccf-86f6-57d30909a23b)
![image](https://github.com/user-attachments/assets/8514ee01-6899-44c7-b05d-6eeeacfca581)
![image](https://github.com/user-attachments/assets/ce32366d-bc60-4d09-8f26-dc5e003c4379)
![image](https://github.com/user-attachments/assets/49a89ab6-0820-4bfe-a1f3-81cbeba215a3)
![image](https://github.com/user-attachments/assets/66e16e47-7be4-4431-ae9a-601d2b09f389)
![image](https://github.com/user-attachments/assets/b3a1fcd2-d1ee-466f-8cc3-0d85d268f22a)
![image](https://github.com/user-attachments/assets/c36c502b-f988-4e08-9bb9-a47268aa8221)
![image](https://github.com/user-attachments/assets/b67ee440-d094-40ae-b317-885dd116c4b4)
![image](https://github.com/user-attachments/assets/e7c2338d-d9db-4b4f-8a82-8c48e67d699e)
![image](https://github.com/user-attachments/assets/5e958a61-2c23-47dd-adc4-78862283d561)
![image](https://github.com/user-attachments/assets/e01b91c0-58e7-4952-bf86-5f0bf19a0d8b)
![image](https://github.com/user-attachments/assets/fd25fcc5-0d88-4722-9119-69985c65daae)
# O/p
![image](https://github.com/user-attachments/assets/5e5c3323-c53f-46b7-9dda-c33b216e5bba)
## SSL Certificate
![image](https://github.com/user-attachments/assets/871a73e8-6b03-4181-bd73-3b17856e4ec9)

