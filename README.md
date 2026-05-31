# issue2mdweb systemctl configuration

```bash
# set up the service file
sudo vi /etc/systemd/system/issue2mdweb.service

# then copy paste in the contents

# service commands:

sudo systemctl daemon-reload
sudo systemctl enable issue2mdweb.service
sudo systemctl start issue2mdweb.service
```
