# controllresource_
> this project for monitor VMware Exsi with vCenter, Telegraf, Prometheus, Grafana.
I split this 3 part, Telegraf config, Prometheus config and Grafana config.

- My project workflow is:
```
vCenter --> Telegraf --> Prometheus --> Grafana
                          |
                          +--> Alert Manager --> alert critical status of system.
```

[+] Metric collect :
  - CPU : usage, free
  - RAM : usage, free
  - DISK : usage, free
  - NETWORK : packets, traffic
