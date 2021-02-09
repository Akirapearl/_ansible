# Ansible portfolio

This repository contains my current ansible configurations to deploy multiple scenarios each of them with different topology.

**Ordered by creation date:**

  1. January-February 2021 -  files_base 
  
        Scenario with two hosts, first one its an Ubuntu based server which runs Apache and shares the default working directory 
        (/var/www/html) with a host client (also running debian/ubuntu based) via nfs ,that path will be mounted into non-root user's home directory.
        The client will be provided with an open source ide to work with (Atom).
        
        ![Image of Network](https://)
        
