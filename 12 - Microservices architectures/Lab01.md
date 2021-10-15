# Microservices architectures
## Lab 1 , The Monolith (LEMP Server)

### Instructions
For this lab, you will deploy a Ghost Blog in an Ubuntu Server using a monolithic architecture.

1. By any means of infrastructure (VirtualBox, VMWare, Docker, AWS, GCP, DigitalOcean) create the server that you will use to deploy the Ghost Blog application. The requirements for this server are:

    | | | |
    | ----------- |-------------| -------:|
    | OS   | Ubuntu LTS 18.04 or 16.04|
    | RAM   | At least 1 GB|

2. You will require a domain name to set up the Ghost Blog. [We recommend creating a new Digital Ocean account and using the free starting credit to secure a cheap domain name for a couple of days](https://docs.digitalocean.com/products/networking/dns/), or getting your own domain name from your provider of preference.

3. [Follow the steps on this tutorial to deploy a Ghost Blog on your server.](https://www.linuxbabe.com/ubuntu/install-ghost-blog-ubuntu) Use mysql as a database and nginx as a reverse proxy.
    - NOTE: The linked tutorial uses MariaDB as a database for the blog, however it is expected you use mysql instead.

### Expected deliverables
- A video of a recording of your screen that showcases your server and the Ghost Blog being reached via a web browser.
- A document in your prefered format containing screenshots and brief descriptions of the steps taken to deploy the monolithic application. 


### Evaluation
| Metric name | Description | % Value |
| ----------- |-------------| -------:|
| Documentation   | Procedure to configure the application was delivered | 50% |
| Functionality   | Application is available via web browser | 50% |
