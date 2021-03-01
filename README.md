# Ansible portfolio

This repository contains my current ansible configurations to deploy multiple scenarios each of them with different topology.

**Ordered by creation date:**

  1. January-February 2021 -  files_base 
  
        Scenario with two hosts, first one its an Ubuntu based server which runs Apache and shares the default working directory 
        (/var/www/html) with a host workstation (also running debian/ubuntu based) via nfs ,that path will be mounted into non-root user's home directory.
        
       The client will be provided with an open source ide to work with (Atom).
        

        ![Image of Network](https://github.com/Akirapearl/_ansible/blob/main/files_base/Topology.png)
       
  2. March - ??? 2021 - files_project01
        
       Taken first scenario as a reference/base point, added an Opensuse machine with the role of DNS, so the topology can keep growing.
       DNS file is provided by Ansible server(pre-configured), service is both installed and fully configured via Ansible too.
        

        ![Image of Network01](https://github.com/Akirapearl/_ansible/blob/main/files_project01/index.png)
