# Ansible portfolio

This repository contains my current ansible configurations to deploy multiple scenarios each of them with different topology.

**Ordered by creation date:**

  1. January-February 2021 -  files_base 
  
        Scenario with two hosts, first one its an Ubuntu based server which runs Apache and shares the default working directory 
        (/var/www/html) with a host client (also running debian/ubuntu based) via nfs ,that path will be mounted into non-root user's home directory.
        The client will be provided with an open source ide to work with (Atom).
        
        ![Image of Network](https://github.com/Akirapearl/_ansible/blob/main/files_base/Topology.png)
       
  2. February - ??? 2021 - files_project01
        
        Scenario with a single client and multiple servers, using diferent services (As web or dns). Deployment with different 
        distributions to achieve knowledge about how to handle diferent packages for each distro. Also introducing a backup for the 
        web server, working again under ubuntu server 20.04 LTS (updated to last point release).
        
        ![Image of Network01](https://github.com/Akirapearl/_ansible/blob/main/files_project01/index.png)
