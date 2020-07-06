### k8s ingress gce multi domain and ssl
- The maximum number of rules for a URL map is 50. This means that you can specify a maximum of 50 rules in an Ingress
- Maximum 15 SSL certificates per GKE Ingress / Load Balancer
- GKE clusters have a limit of 1000 nodes. When services are deployed with NEGs, there is no GKE node limit
- Combining multiple Ingress resources into a single Google Cloud load balancer is not supported
![alt text](https://miro.medium.com/max/1400/1*KIVa4hUVZxg-8Ncabo8pdg.png)
