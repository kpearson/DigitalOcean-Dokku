DigitalOcean-Dokku
==================

Digital Ocean + Dokku deployment notes.


1. Digital Ocean create account.
2. Create a new droplet using the latest Ubuntu making sure you select your ssh key.
    If the ssh key is missed adding it later is easy enough 
    following this https://www.digitalocean.com/community/articles/how-to-set-up-ssh-keys--2
      
    However I needed to install `ssh-copy-id` command
    To do this I used
    `https://www.digitalocean.com/community/articles/how-to-set-up-ssh-keys--2`,
    Followed by
    `sudo chmod +x /usr/local/bin/ssh-copy-id`
      
3. As soon as your server is ready you can connect via SSH

      `$ ssh root@_new_droplet_ip`
      
4. Install dokku on the new VSM Vertual


