**How this scenario actually works**
# First of all, im sorry for any english typing error.
        
	0 - This project assumes that you already have basic knowledges about ansible. If not, go to Learn Linux Tv's youtube
	    channel, it has a free introduction series. 

	1- Change the inventory file with your IPs, [nfs_server] and [nfs_client] are only to clarify, dont have any usage
	   into yml files.
	
	2- Change the exports file with the nfs settings that suits your needs.
	   [ WARNING! ] - playbook.yml has my own path to store exports file, change it to your own, this is a must do thing to 
	   make the playbook work correctly.
	
	3- [ Optional ] Delete /extra/192.168.10.9/ directory, it has my own fstab for this scenario, 
	   wont be that useful. Only added as a guide to anyone that has never edited fstab file.
	   [ WARNING! ] - playbook.yml has my own path to save fstab file, change it to your own, this is a must do thing to 
	   make the playbook work correctly.
	

	4- Execute playbook.yml

	5- Go to your imported fstab's directory, add the nfs mountpoint.
	  [ WARNING! ] - playbook_2.yml has my own path to save fstab file, change it to your own, this is a must do thing to 
	  make the playbook work correctly.

	6 - Execute playbook_2.yml

	7 - Are you ready to code?!


**Improvements to be made**

	1- Add mysql server (same ip?) with php module if exists/required
	2- Allow non-root user in client to write and change files without root's password
	3- Introduce Variables to directories, so its "easier" to work arround exports and fstab files.

        ![Working](https://github.com/Akirapearl/_ansible/blob/main/files_base/extra/Test_playbook2_nfs.png)
        
