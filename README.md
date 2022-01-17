# Raspberry_pi_Shiny_app
This project will include all the materials used in the 19th January 2022 Webinar for the NHS-R Community

Designing a Shiny dashboard using a Raspberry Pi cluster

- This presentation describes<br>the steps required to setup a Raspberry Pi cluster and preparations needed to turn it into a Shiny Server

In the NHS-R Community Webinar on Wednesday 19th, the presentation will cover these four topics: 
-1.Different ways of connecting remotely to the Raspberry Pi
-2.How to setup a Raspberry pi cluster, 
-3.Generate a SSH key on Windows to log into each Raspberry Pi's in the Cluster
-4.Briefly description of the process to create a Shiny server (following R Studio Community blog posts)



- Online resources used to build the presentation
**1. Generate SSH Keys on Windows and copy them to your Raspberry Pi cluster
https://pimylifeup.com/raspberry-pi-ssh-keys/

**2.Setting up your own shiny-server / rstudio-server on a Raspberry Pi 3B+
https://community.rstudio.com/t/setting-up-your-own-shiny-server-rstudio-server-on-a-raspberry-pi-3b/18982

This is the main blog post that details the steps required to setup a Shiny server on a Raspberry pi. 
**RStudio Community**
- Andrés Castro Socolich
- https://community.rstudio.com/u/andresrcs


Preparing the Raspberry Pi

1. Install Raspbian OS
2. Set a static IP for our raspberry pi
3. Setting up the Server
3.1 We will use an HTML server, he uses Nginx 
3.2 Install Nginx 
4. Then we need a sql server for storing and manipulating our data
4.1 Install PostgreSQL it is open-source 
4.2 Configure postgresql to accept local and remote connections
4.3 Restart postgresql service
5. Install the latest version of R from source
6. Install Shiny-Server
7. Configure Shiny-Server
8. Install R Studio from source
9. Extra steps
10. Make pretty URLs for Shiny and Rstudio Server
11. To access you shiny app from anywehere over the internet, create a static public IP

This is an experimental project to test how it would be posible to run a Shiny app 24/7 from a Server setup in a Raspberry Pi cluster, an inexpensive way of designing a Shiny web app that people can access over the internet. 

All the credits and original ideas goes to the original developers of the different resources I have used to put together the required materials for this project. 
