### Kill running Nodejs

`$ killall node`

### Restart NGINX   
`$ sudo systemctl restart nginx`

### Start PM2       

`$pm2 start npm --name "xxx" –start`

### Make ssh key 

`$ ssh-keygen`

### Copy SSH Public Key 

`$ ~/.ssh/id_rsa.pub`

### Kill all running Docker containers 

`docker kill $(docker ps -q)`


### Deploy local files to server (example using uploads folder)

`$ scp -r ~/Downloads/uploads/* root@IP_HOST:FULL_PATH_GOES_HERE/wp-content/uploads`
