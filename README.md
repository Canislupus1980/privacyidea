# privacyidea
install pivacyidea server

###Passwd admin:###

sudo docker exec -it privacyidea pi-manage admin add admin

sudo docker exec -it privacyidea pi-manage policy create welcome_disable webui hide_welcome_info
