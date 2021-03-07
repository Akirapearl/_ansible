# First of all, a little introduction

This part of the repository is intended to be my next learning step arround ansible, also will be used as reference,
futurely i plan to update and improve this and previous part with more in-depth configs, but for now im just playing arround
with thing i want to know and learn.


This part has been created to figure out how to work with service (dns for this scenario), copying the .conf file
to the ansible server and modify it remotely, then, as i did before with fstab, having a second playbook will help to 
return that modified file to the dns server, then reload the service so it should work as it was modified in the target server. 


This time its also introduced a opensuse tumbleweed server, this is because i dont want to work only with apt module for debian
family (Ubuntu etc) so im not stucked in just one or two distros, might create some sentences to be able to use fedora/rhel as well.


# How this scenario actually works
        
	0 - This project assumes that you already have basic knowledges about ansible. If not, go to Learn Linux Tv's youtube
	    channel, it has a free introduction series.

	1-  
