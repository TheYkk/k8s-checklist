# K8S  Knowledge Checklist

## Checklist
### K8S Setup
- Managed
	- [ ] [GKE](https://cloud.google.com/kubernetes-engine)
	- [ ] [EKS](https://aws.amazon.com/eks/)
	- [ ] [AKS](https://azure.microsoft.com/en-us/services/kubernetes-service/)
	- [ ] [Digital Ocean](https://www.digitalocean.com/products/kubernetes/)
	- [ ] [Okteto Cloud](https://okteto.com/)
	- [ ] [Civo Cloud](https://www.civo.com/)
- On Premise
	- [ ] [Kubeadm](https://github.com/kubernetes/kubeadm)
	- [ ] [Kops](https://github.com/kubernetes/kops)
	- [ ] [Kubespray](https://github.com/kubernetes-sigs/kubespray)
	- [ ] [Microk8s](https://microk8s.io/)
	- [ ] [K3S](https://k3s.io/)
- For Development
	- [ ] [K3D](https://k3d.io/)
	- [ ] [Kind](https://kind.sigs.k8s.io/)
	- [ ] [Minikube](https://minikube.sigs.k8s.io/docs/)
### K8S Resources

### [Security](https://kubernetes.io/docs/concepts/security/)
- Falco 
### Backup
### [Networking](https://kubernetes.io/docs/concepts/services-networking/)
- [CNI](https://github.com/containernetworking/cni)
	- [ ] [Canal](https://github.com/projectcalico/canal)
	- [ ] [Cillium](https://cilium.io/)
	- [ ] [WeaveNet](https://www.weave.works/docs/net/latest/overview/)
	- [ ] [Flannel](https://github.com/flannel-io/flannel)
	- [ ] [Calico](https://www.projectcalico.org/)
### [Ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/)

### [Service Mesh](https://www.redhat.com/en/topics/microservices/what-is-a-service-mesh)

### Logging
- Stacks
	- [ ] [ELK](https://www.elastic.co/what-is/elk-stack) (Elasticsearch, Logstash, Kibana)
	- [ ] EFK (Elasticsearch, fluentd (or fluentbit), Kibana)
	- [ ] Loki stack (Promtail, Loki, Grafana)
- Hosted
	- [ ] [Logz](https://logz.io/)
	- [ ] [LogDNA](https://www.logdna.com/) 
	- [ ] [Datadog](https://www.datadoghq.com/)
### CI/CD
- Pull based
	- [ ] [Argo CD](https://argoproj.github.io/argo-cd/)
- Push based
	- [ ] [Gitlab CI](https://docs.gitlab.com/ee/ci/)
	- [ ] [Github Actions](https://github.com/features/actions)
### Monitoring
-	[Prometheus](https://prometheus.io/)
	-	[ ] I deployed Prometheus with default configs
	-	[ ] I wrote scraping config
	-	[ ] I used Prometheus Federation
	-	[ ] I wrote PromQL
-	[Alert Manager](https://prometheus.io/docs/alerting/latest/alertmanager)
	-	[ ] I deployed Alert Manager with default configs
	-	[ ] I edit alert template
	-	[ ] I wrote alert condition
	-	[ ] I enabled Slack notification
	-	[ ] I used another notification settings (webhooks)
-	[Grafana](https://grafana.com/grafana/)
	-	[ ] I deployed Grafana with default configs
	-	[ ] I connect Prometheus to Grafana
	-	[ ] I created new Grafana Dashboard
	-	[ ] I configured Grafana to work as stateless
-	[Metrics Server](https://github.com/kubernetes-sigs/metrics-server)
	-	[ ] I deployed Metrics Server with default configs
- Extra
	- [ ] [Netdata](https://www.netdata.cloud/) 
- Hosted Monitoring
	- [ ] [Datadog](https://www.datadoghq.com/)
	- [ ] [New Relic](https://newrelic.com/)



## Additional Resources
