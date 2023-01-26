
Service files install

```
sudo cp porcupine.service /lib/systemd/system/porcupine.service 
sudo systemctl daemon-reload
sudo systemctl restart porcupine
journalctl -fu porcupine
  ```
