# K8S  Knowledge Checklist

## Checklist
### K8S Setup
- Managed
	- [ ] GKE
	- [ ] EKS
	- [ ] AKS
	- [ ] Digital Ocean
	- [ ] Okteto Cloud
	- [ ] Civo Cloud
- On Premise
	- [ ] Kubeadm
	- [ ] Kops
	- [ ] Kubespray
	- [ ] Minikube
	- [ ] Microk8s
	- [ ] K3S

### Security
- Falco 
### Backup
### Networking
- [CNI](https://github.com/containernetworking/cni)
	- [ ] Canal
	- [ ] Cillium
	- [ ] WaweWorks
	- [ ] Flannel
	- [ ] Calico
### [Ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/)

### [Service Mesh](https://www.redhat.com/en/topics/microservices/what-is-a-service-mesh)

### Logging
- Stacks
	- [ ] ELK (Elasticsearch, Logstash, Kibana)
	- [ ] EFK (Elasticsearch, fluentd (or fluentbit), Kibana)
	- [ ] Loki stack (Promtail, Loki, Grafana)
- Hosted
	- [ ] Logz
	- [ ] LogDNA 
	- [ ] Datadog
### CI/CD
- Pull based
	- [ ] Argo CD
- Push based
	- [ ] Gitlab CI
	- [ ] Github Actions
### Monitoring
-	Prometheus
	-	[ ] I deployed Prometheus with default configs
	-	[ ] I wrote scraping config
	-	[ ] I used Prometheus Federation
	-	[ ] I wrote PromQL
-	Alert Manager
	-	[ ] I deployed Alert Manager with default configs
	-	[ ] I edit alert template
	-	[ ] I wrote alert condition
	-	[ ] I enabled Slack notification
	-	[ ] I used another notification settings (webhooks)
-	Grafana
	-	[ ] I deployed Grafana with default configs
	-	[ ] I connect Prometheus to Grafana
	-	[ ] I created new Grafana Dashboard
	-	[ ] I configured Grafana to work as stateless
-	Metrics Server
	-	[ ] I deployed Metrics Server with default configs
- Extra
	- [ ] Netdata 
- Hosted Monitoring
	- [ ] Datadog
	- [ ] New Relic



## Additional Resources
