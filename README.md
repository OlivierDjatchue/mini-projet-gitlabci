## Firstname : Olivier

## Surname : Djatchue-Tchokothe

## For Eazytraining's 18th DevOps Bootcamp

## Period : march-april-may


## GitLab CI Pipeline for Dockerized Application
This project demonstrates the setup of a CI/CD pipeline using GitLab CI for a Dockerized application. The pipeline includes building, testing, and deploying the application to Heroku.

# Table of Contents
Pipeline Steps
>> 1. Build Docker Image
>> 2. Test Docker Image
>>3. Load and Tag Docker Image
>>4. Deploy to Staging
>>6. Deploy to Production
>>7. Test Staging Environment
>>8. Test Production Environment
>>9. Screenshots
>>10. Conclusion
>>11. What I've Learned


# Pipeline Steps
1)  Build Docker Image
The pipeline begins with building a Docker image using a Dockerfile. This step ensures that the application is containerized and can run consistently across different environments.

>![docker-build0](https://github.com/user-attachments/assets/ae8b0033-a62f-49a4-9c02-f7aa258b4ed8)
2. Test Docker Image
After building the image, the pipeline tests it to verify that the application works as expected within the Docker container.

>![image](https://github.com/user-attachments/assets/ccc86747-bd18-463f-92ef-e35cfedc80de)


4. Load and Tag Docker Image
This step loads the Docker image from the api.tar artifact, tags it with the branch name and commit SHA, and then pushes it to the GitLab registry.

>![image](https://github.com/user-attachments/assets/4a6ba540-d467-4074-82f1-12ae3cc8fe2a)


6. Deploy to Staging
Deploy the Dockerized application to a Heroku staging environment for further testing.
>![image](https://github.com/user-attachments/assets/6e64c59a-1197-4f2f-9a12-f19c098a6218)

9. Deploy to Production
Once the application passes the staging tests, it is deployed to the Heroku production environment.
>![image](https://github.com/user-attachments/assets/ec3ff0e4-ca78-4c6d-912c-c9fa152dd059)


8. Test Staging Environment
After deployment, the pipeline tests the application in the staging environment to ensure everything is functioning correctly.
>![image](https://github.com/user-attachments/assets/add528e8-b069-4de7-958b-df8795967c79)


10. Test Production Environment
Finally, the pipeline tests the production environment to confirm the application is live and operational.

 > ![image](https://github.com/user-attachments/assets/cdc7a6d0-e69a-48d8-871d-8f0e46ff19fc)

# Screenshots
Pipeline Overview
> ![overview pipeline](https://github.com/user-attachments/assets/ddfc4233-879e-4761-b7a5-a2b99b3b98c7)



Docker Image Build
> ![docker-build](https://github.com/user-attachments/assets/cb7673a3-512b-41d8-a582-d35aa4263e84)

Release the image
> ![release_images](https://github.com/user-attachments/assets/43f069bd-53b0-42d1-af36-6a78ee50d851)

Staging Deployment
> ![deploy_staging](https://github.com/user-attachments/assets/15461278-278b-4bfb-a0b0-a54ab6ea6506)

Production Deployment
> ![deploy_prod](https://github.com/user-attachments/assets/1de0b773-a316-47cd-8881-ee0c61ad1f57)
Test Staging

Test Staging Environment
> ![test_staging](https://github.com/user-attachments/assets/c7a67d5b-32d6-4be6-a992-e08f3fe77b56)

Test production Environment
> ![test_prod](https://github.com/user-attachments/assets/b94d0a62-2683-4f34-8161-5352feea9182)

App overview on Heroku
>![app_overview in heroku](https://github.com/user-attachments/assets/e94dde93-08c7-4e90-9b9c-5c9b492c14d8)

Opening the App in the webbrowser
> ![viewing the app](https://github.com/user-attachments/assets/585771fb-9038-4c1c-8c04-b390d6a02492)

## Conclusion
Throughout this project, I have learned to set up a robust CI/CD pipeline using GitLab CI. The process includes building and testing Docker images, deploying to Heroku, and ensuring that applications are working in both staging and production environments.

## What I've Learned
1) CI/CD Best Practices: Gained a deep understanding of continuous integration and continuous deployment practices.
2) Docker Proficiency: Improved skills in containerizing applications using Docker.
3) Heroku Deployments: Learned to deploy applications to Heroku using Docker.
4) Pipeline Automation: Automated complex workflows, improving efficiency and reducing manual intervention.
These skills are valuable for automating application deployments, ensuring consistent and reliable software delivery, and improving overall DevOps practices.
