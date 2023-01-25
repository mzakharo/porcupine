
Service files install

```
sudo cp porcupine.service /lib/systemd/system/porcupine.service 
sudo systemctl daemon-reload
sudo systemctl restart 
journalctl -fu porcupine
  ```
