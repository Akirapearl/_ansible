# ansible portfolio

This repository contains my current ansible configurations to deploy multiple scenarios each of them with different topology.

Ordered by creation date:

  1. files_base 
        Scenario with two hosts, first one its an Ubuntu based server which runs an Apache web server and
        shares the /var/www/html directory (default to apache) with the client (also debian/ubuntu based), that
        path will be mounted into non-root user's home directory.
        
        ![Image of Network](https://)
        
