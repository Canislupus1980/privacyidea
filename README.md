![privacyidea](https://daasi.de/wp-content/uploads/2021/04/privacyIDEA-800px-300x162.png)
# Privacyidea
## Install pivacyidea server

### Passwd admin
```bash
sudo docker exec -it privacyidea pi-manage admin add admin
```
### Remove start reminder
```bash
sudo docker exec -it privacyidea pi-manage policy create welcome_disable webui hide_welcome_info
```
