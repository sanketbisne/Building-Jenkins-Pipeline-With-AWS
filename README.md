# Building-Jenkins-Pipeline-With-AWS
Build CI/CD Pipelines, Monitoring, and Logging
 
 Jenkins is an automation server that is used to automate the tasks associated with CI/CD, such as building, testing, and deploying the application. 

AWS Pipeline Service 
    AWS CodeBuild and AWS CodeDeploy are the two most relevant services that are useful as a part of DevOps.

#FINAL PREVIEW OF WEBPAGE 

Here We deployed a Static website which uses the Concept of Continuous Integration and Continuous Deployment With JEnkins Over AWS




![Screenshot from 2020-06-27 18-20-38](https://user-images.githubusercontent.com/38061560/85928779-47c32800-b8cd-11ea-8b67-96e112bb8269.png)
FINAL CLOUD DEPLOYMENT RUNNING WEBPAGE OVER S3




Welcome to AWS World
![Screenshot from 2020-06-27 23-49-11](https://user-images.githubusercontent.com/38061560/85929254-f5840600-b8d0-11ea-83b2-44aef0946565.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Add Instance
 OS-UBUNTU

 AMI-t2.micro (free Tier)

ADD tag as Jenkins

add Security Group 8080 port and ssh 22

ssh because we  have to do remote  login to our pc

Add IAM Users

Add polices MinimumSecurity Model

under -s3fullaccess,vpc and ec2

create policies 

create Groups

Add Users

Login to IAM User

install Jenkins 

Run it on Port 8080

Configure it

Add All BlueOcean  Plugins

Add  Credentials of IAM USERS 

Open BlueOcean

Create Pipeline

Add Github Repository

Add Secret key
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
OPEN ANY IDE
CREATE Jenkinsfile->Add Stages To it
CREATE html bare file to took a pull to jenkins and Deploy over S3
Create Build

Create Stages 

Build->Test->Deploy

 **LINTING**

After adding a linter, it catches HTML problems with the sample index.html, after addressing the problems with the html, the job passes and publishes the contents once again - build is passing. 

 **Jenkinsfile**

A Jenkinsfile exists, that has the stages and steps defined that match how the pipeline looks in the Jenkins dashboard. For example ‘stage(‘Lint HTML’)’ should show as ‘Lint HTML’ in the pipeline. The AWS credentials and bucket name should all map to an existing S3 bucket that is publicly accessible and that it displays the contents of the index.html file.

  **Publishes the static site to S3**
  | The index.html file is published to the correct bucket in  the right region, and the url is accessible via HTTP from anywhere

That's All your are in Clouds Now


![Screenshot from 2020-06-27 23-49-11](https://user-images.githubusercontent.com/38061560/85929718-ba83d180-b8d4-11ea-9f52-0e1b5fd054a2.png)

![Screenshot from 2020-06-25 11-57-22](https://user-images.githubusercontent.com/38061560/85929816-7c3ae200-b8d5-11ea-9183-2a4fe0c1c1b1.png)
![Screenshot from 2020-06-25 11-58-12](https://user-images.githubusercontent.com/38061560/85929819-83fa8680-b8d5-11ea-9f43-a1402cc6516a.png)
![Screenshot from 2020-06-25 11-58-18](https://user-images.githubusercontent.com/38061560/85929832-8eb51b80-b8d5-11ea-8871-17e304315bfe.png)
![Screenshot from 2020-06-25 11-58-43](https://user-images.githubusercontent.com/38061560/85929834-95dc2980-b8d5-11ea-81aa-526f6dabf2a6.png)
![Screenshot from 2020-06-25 11-58-56](https://user-images.githubusercontent.com/38061560/85929841-9bd20a80-b8d5-11ea-8b11-c7dd04408b88.png)
![Screenshot from 2020-06-25 11-59-00](https://user-images.githubusercontent.com/38061560/85929852-a4c2dc00-b8d5-11ea-9a99-791e4f39a3db.png)
![Screenshot from 2020-06-25 11-59-06](https://user-images.githubusercontent.com/38061560/85929853-ab515380-b8d5-11ea-9aeb-155131445edd.png)
![Screenshot from 2020-06-25 12-00-54](https://user-images.githubusercontent.com/38061560/85929872-cde36c80-b8d5-11ea-99f8-20b9a3c1b851.png)
![Screenshot from 2020-06-25 12-09-22](https://user-images.githubusercontent.com/38061560/85929902-fc614780-b8d5-11ea-823d-55bbb239f6b5.png)
![Screenshot from 2020-06-25 12-29-46](https://user-images.githubusercontent.com/38061560/85929905-008d6500-b8d6-11ea-8a1d-4a6180bddd50.png)
![Screenshot from 2020-06-25 16-26-23](https://user-images.githubusercontent.com/38061560/85929909-084d0980-b8d6-11ea-99fe-5292e32b6b04.png)
![Screenshot from 2020-06-25 16-36-31](https://user-images.githubusercontent.com/38061560/85929914-0c792700-b8d6-11ea-8ef4-994e41370b3f.png)
![Screenshot from 2020-06-25 17-34-55](https://user-images.githubusercontent.com/38061560/85929920-16028f00-b8d6-11ea-90b0-4a9300c292d2.png)
![Screenshot from 2020-06-25 17-35-47](https://user-images.githubusercontent.com/38061560/85929928-20248d80-b8d6-11ea-98f3-57d99c1f8aa0.png)
![Screenshot from 2020-06-25 17-39-46](https://user-images.githubusercontent.com/38061560/85929932-261a6e80-b8d6-11ea-899f-56bdcec886d5.png)
![Screenshot from 2020-06-25 17-52-17](https://user-images.githubusercontent.com/38061560/85929938-2b77b900-b8d6-11ea-8093-9401c6ccfc8d.png)
![Screenshot from 2020-06-25 17-54-33](https://user-images.githubusercontent.com/38061560/85929944-316d9a00-b8d6-11ea-9e08-abd6bed6fbc6.png)
![Screenshot from 2020-06-25 18-00-05](https://user-images.githubusercontent.com/38061560/85929946-35012100-b8d6-11ea-845a-e95bf7c89cca.png)
![Screenshot from 2020-06-25 18-00-12](https://user-images.githubusercontent.com/38061560/85929947-37fc1180-b8d6-11ea-83ce-329c00c52d3d.png)
![Screenshot from 2020-06-25 18-00-18](https://user-images.githubusercontent.com/38061560/85929950-3a5e6b80-b8d6-11ea-9f63-5e9ea448b450.png)
![Screenshot from 2020-06-25 18-04-06](https://user-images.githubusercontent.com/38061560/85929951-3cc0c580-b8d6-11ea-8c97-e709072d9a0f.png)
![Screenshot from 2020-06-25 21-03-35](https://user-images.githubusercontent.com/38061560/85929957-45190080-b8d6-11ea-9736-65f11a683630.png)
![Screenshot from 2020-06-26 08-36-17](https://user-images.githubusercontent.com/38061560/85929975-57933a00-b8d6-11ea-8b27-1d6c4bd8b1cb.png)
![Screenshot from 2020-06-26 16-44-22](https://user-images.githubusercontent.com/38061560/85929982-64179280-b8d6-11ea-8245-e3787b06e0d7.png)
![Screenshot from 2020-06-26 17-39-28](https://user-images.githubusercontent.com/38061560/85930000-89a49c00-b8d6-11ea-9de0-168b9a574f4b.png)
![Screenshot from 2020-06-26 23-45-27](https://user-images.githubusercontent.com/38061560/85930010-95905e00-b8d6-11ea-9837-5afcea46cc66.png)


Opening Jenkins

![Screenshot from 2020-06-27 23-36-20](https://user-images.githubusercontent.com/38061560/85931426-1012ab00-b8e2-11ea-9282-dad820f12376.png)
![Screenshot from 2020-06-27 23-38-32](https://user-images.githubusercontent.com/38061560/85931429-130d9b80-b8e2-11ea-98ab-6ae5a74b3e52.png)
![Screenshot from 2020-06-27 23-39-16](https://user-images.githubusercontent.com/38061560/85931430-143ec880-b8e2-11ea-9e30-0c8cd851e922.png)
![Screenshot from 2020-06-27 23-39-31](https://user-images.githubusercontent.com/38061560/85931434-16a12280-b8e2-11ea-89fc-db57ac7f1684.png)
![Screenshot from 2020-06-27 23-39-49](https://user-images.githubusercontent.com/38061560/85931438-186ae600-b8e2-11ea-8dda-6af52d671e74.png)
![Screenshot from 2020-06-27 23-40-21](https://user-images.githubusercontent.com/38061560/85931441-1b65d680-b8e2-11ea-8b07-43627ebbd8f3.png)
![Screenshot from 2020-06-27 23-40-51](https://user-images.githubusercontent.com/38061560/85931443-1dc83080-b8e2-11ea-8559-3e4dd93ded05.png)
![Screenshot from 2020-06-27 23-40-59](https://user-images.githubusercontent.com/38061560/85931444-1ef95d80-b8e2-11ea-9dc9-021654797af4.png)
![Screenshot from 2020-06-26 23-45-38](https://user-images.githubusercontent.com/38061560/85931177-13a53280-b8e0-11ea-8d6f-35a231584596.png)
![Screenshot from 2020-06-26 23-50-20](https://user-images.githubusercontent.com/38061560/85931186-1e5fc780-b8e0-11ea-86ee-def006e2d902.png)
![Screenshot from 2020-06-27 10-23-22](https://user-images.githubusercontent.com/38061560/85931191-2b7cb680-b8e0-11ea-8588-a74b93b9b0cf.png)
![Screenshot from 2020-06-27 17-09-19](https://user-images.githubusercontent.com/38061560/85931196-35061e80-b8e0-11ea-8dad-e3d045d6b3ff.png)
![Screenshot from 2020-06-27 17-09-28](https://user-images.githubusercontent.com/38061560/85931199-37687880-b8e0-11ea-9a26-c4656c9dee73.png)
![Screenshot from 2020-06-27 17-23-22](https://user-images.githubusercontent.com/38061560/85931201-3a636900-b8e0-11ea-8970-317b5a8ee59d.png)
![Screenshot from 2020-06-27 17-25-31](https://user-images.githubusercontent.com/38061560/85931202-3c2d2c80-b8e0-11ea-8939-bd917a7ec360.png)
![Screenshot from 2020-06-27 17-57-28](https://user-images.githubusercontent.com/38061560/85931203-3d5e5980-b8e0-11ea-8053-822e3601afae.png)
![Screenshot from 2020-06-27 17-59-02](https://user-images.githubusercontent.com/38061560/85931206-3f281d00-b8e0-11ea-99b5-fb947ac65f5e.png)
![Screenshot from 2020-06-27 18-20-38](https://user-images.githubusercontent.com/38061560/85931413-f709fa00-b8e1-11ea-9991-3ed86bb49b82.png)

![Screenshot from 2020-06-27 23-41-16](https://user-images.githubusercontent.com/38061560/85931445-20c32100-b8e2-11ea-8cdb-24f85caea3b3.png)
![Screenshot from 2020-06-27 23-42-24](https://user-images.githubusercontent.com/38061560/85931448-21f44e00-b8e2-11ea-9d27-ffd450c967c0.png)
![Screenshot from 2020-06-27 23-42-48](https://user-images.githubusercontent.com/38061560/85931450-23be1180-b8e2-11ea-99c2-4232ec6b2ba3.png)
![Screenshot from 2020-06-27 23-43-02](https://user-images.githubusercontent.com/38061560/85931453-2587d500-b8e2-11ea-9529-558e685faa43.png)
![Screenshot from 2020-06-27 23-43-49](https://user-images.githubusercontent.com/38061560/85931456-27ea2f00-b8e2-11ea-8bc2-186d3f95d3f3.png)








































