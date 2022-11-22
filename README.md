# Build-Solutions-Across-VPCs-with-AWS-Peering

![ScreenShot](https://github.com/NavarroAlexKU/Build-Solutions-Across-VPCs-with-AWS-Peering/blob/main/VPC%20Peering.png)

## Project Objective:
Create a new VPC for WordPress blog to run from. Create a VPC peering connection between your new VPC and existing database VPC.

## Author:
[Alex Navarro]
[https://github.com/NavarroAlexKU]

## 🔗 Social Media Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alexnavarro2/)

## Project Walk Through:

* First, login to AWS Console and search VPC in the Search bar:

![ScreenShot](https://github.com/NavarroAlexKU/Build-Solutions-Across-VPCs-with-AWS-Peering/blob/main/Screenshot%202022-11-22%20at%2010.07.21%20AM.png)

* After clicking on VPC, we can see we have a VPC already created called DB_VPC

![ScreenShot](https://github.com/NavarroAlexKU/Build-Solutions-Across-VPCs-with-AWS-Peering/blob/main/Screenshot%202022-11-22%20at%2010.10.05%20AM.png)

* Next, we will go to our DB instance and we can see that it's showing up under Resources.

![ScreenShot](https://github.com/NavarroAlexKU/Build-Solutions-Across-VPCs-with-AWS-Peering/blob/main/Screenshot%202022-11-22%20at%2010.13.01%20AM.png)

* Next we will create a new VPC:
    - Click 'Create VPC'
    - Resources to create will be VPC Only
    - Name is Web_VPC
    - IPv4 CIDR we will use the following IP address 192.168.0.0/16 "lab IP Address"
    - Everything else we can leave as default and click "Create VPC"

    ![ScreenShot](https://github.com/NavarroAlexKU/Build-Solutions-Across-VPCs-with-AWS-Peering/blob/main/Screenshot%202022-11-22%20at%2010.18.14%20AM.png)

* Nexdt, we will create a Subnet:
    - In left navigation pane, click "Subnets"
    - Click "Create Subnets"
    
    ![ScreenShot](https://github.com/NavarroAlexKU/Build-Solutions-Across-VPCs-with-AWS-Peering/blob/main/Screenshot%202022-11-22%20at%2010.22.42%20AM.png)
