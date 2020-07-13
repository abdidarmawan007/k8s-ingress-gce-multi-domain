## k8s ingress gce multi domain and managed ssl
- Minimum version 1.16.5-gke.1  for support version v1beta2 ManagedCertificate (multiple domain names per certificate)
- The maximum number of rules for a URL map is 50. This means that you can specify a maximum of 50 rules in an Ingress
- Managed certificates support up to 100 non-wildcard domains, whereas self-managed certificates can support wildcards
- GKE clusters have a limit of 1000 nodes. When services are deployed with NEGs, there is no GKE node limit

### url for increase quota ingress url maps,ssl etc
```
https://cloud.google.com/load-balancing/docs/quotas#url_maps
https://cloud.google.com/load-balancing/docs/quotas#ssl_certificates
https://cloud.google.com/load-balancing/docs/quotas#target_pools_and_target_proxies
https://cloud.google.com/load-balancing/docs/quotas#backend_services
```

![alt text](https://miro.medium.com/max/1400/1*KIVa4hUVZxg-8Ncabo8pdg.png)
