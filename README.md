#Use below commands in Jenkins Build steps

sudo git clone <Repo URL>

sudo mkdir wordpress/nginx-conf

sudo cp /home/azureuser/wordpress/nginx.conf /home/azureuser/wordpress/nginx-conf/nginx.conf

sudo chmod 774 /home/azureuser/wordpress/composer.sh

sudo wordpress/composer.sh
