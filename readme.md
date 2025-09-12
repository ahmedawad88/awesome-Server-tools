# Awesome Server Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome tools and services for **server deployment, management, and operations**. Includes both open-source self-hosted projects and cloud services, organized by functionality.  
**Contributions welcome!** Follow the [Awesome guidelines](https://github.com/sindresorhus/awesome/blob/main/contributing.md).

---

## Contents

- [Deployment & Provisioning](#deployment--provisioning)
- [Monitoring & Alerting](#monitoring--alerting)
- [Backup & Recovery](#backup--recovery)
- [Logging & Tracing](#logging--tracing)
- [Load Balancing & Proxying](#load-balancing--proxying)
- [Configuration Management](#configuration-management)
- [Security & Firewalls](#security--firewalls)
- [Web Servers & Reverse Proxies](#web-servers--reverse-proxies)
- [Performance & Optimization](#performance--optimization)
- [Remote Access & Terminal Management](#remote-access--terminal-management)
- [Containers & Virtualization](#containers--virtualization)
- [Serverless & Cloud Services](#serverless--cloud-services)
- [Contributing](#contributing)
- [License](#license)

---

## Deployment & Provisioning

- [Terraform](https://github.com/hashicorp/terraform) – IaC for multi-cloud/on-prem.
- [AWS CloudFormation](https://aws.amazon.com/cloudformation/) – AWS IaC via YAML/JSON templates.
- [Pulumi](https://www.pulumi.com/) – IaC with real programming languages.
- [Packer](https://github.com/hashicorp/packer) – Automated VM/container image builds.
- [Vagrant](https://www.vagrantup.com/) – Reproducible dev VMs & environments.
- [Capistrano](https://github.com/capistrano/capistrano) – SSH app deployment (Ruby).
- [Fabric](https://www.fabfile.org/) – SSH automation (Python).
- [Foreman](https://theforeman.org/) – Lifecycle management & provisioning.
- [Cobbler](https://github.com/cobbler/cobbler) – Network/PXE OS provisioning.
- [Spinnaker](https://spinnaker.io/) – Multi-cloud continuous delivery.

## Monitoring & Alerting

- [Prometheus](https://prometheus.io/) – Metrics & alerting (CNCF).
- [Grafana](https://grafana.com/) – Dashboards & visualization.
- [Nagios](https://www.nagios.org/) – Classic host/service monitoring.
- [Zabbix](https://www.zabbix.com/) – Enterprise infra monitoring.
- [Icinga](https://icinga.com/) – Modern Nagios fork + API.
- [Netdata](https://www.netdata.cloud/) – Real-time per-second monitoring.
- [Datadog](https://www.datadoghq.com/) – SaaS observability platform.
- [New Relic](https://newrelic.com/) – APM & infra monitoring.
- [PagerDuty](https://www.pagerduty.com/) – Incident & on-call management.
- [Checkmk](https://checkmk.com/) – Comprehensive monitoring suite.

## Backup & Recovery

- [Bacula](https://www.bacula.org/) – Enterprise backup suite.
- [BorgBackup](https://www.borgbackup.org/) – Deduplicating encrypted backups.
- [Restic](https://restic.net/) – Fast, secure backups to many backends.
- [Duplicati](https://www.duplicati.com/) – Encrypted backups with web UI.
- [rsnapshot](https://rsnapshot.org/) – rsync-based snapshot backups.
- [UrBackup](https://www.urbackup.org/) – Client/server file & image backups.
- [Rclone](https://rclone.org/) – Sync/backup to cloud storage.
- [Velero](https://velero.io/) – Kubernetes backups & DR.

## Logging & Tracing

- [Elastic Stack (ELK)](https://www.elastic.co/elastic-stack/) – Elasticsearch, Logstash/Beats, Kibana.
- [Graylog](https://www.graylog.org/) – Centralized log management.
- [Grafana Loki](https://grafana.com/oss/loki/) – Cost-effective log aggregation.
- [Splunk](https://www.splunk.com/) – Enterprise log analytics (commercial).
- [Sentry](https://sentry.io/) – Error tracking & performance.
- [Jaeger](https://www.jaegertracing.io/) – Distributed tracing (CNCF).
- [Zipkin](https://zipkin.io/) – Distributed tracing.
- [Fluentd](https://www.fluentd.org/) – Unified log data collector.

## Load Balancing & Proxying

- [HAProxy](http://www.haproxy.org/) – High-performance L4/L7 load balancer.
- [Traefik](https://traefik.io/) – Cloud-native reverse proxy/ingress.
- [Envoy](https://www.envoyproxy.io/) – High-performance service proxy.
- [Nginx](https://nginx.org/) – Web server & reverse proxy.
- [Apache Traffic Server](https://trafficserver.apache.org/) – Caching proxy/LB.
- [NGINX Plus](https://www.nginx.com/products/nginx/) – Nginx with enterprise features.
- [AWS Elastic Load Balancing](https://aws.amazon.com/elasticloadbalancing/) – Managed L4/L7 load balancers.
- [Cloudflare](https://www.cloudflare.com/) – Edge proxy, CDN, LB, security.
- [Kong](https://konghq.com/kong) – API gateway on Nginx.

## Configuration Management

- [Ansible](https://www.ansible.com/) – Agentless automation with YAML playbooks.
- [Puppet](https://puppet.com/) – Declarative CM with agent/master.
- [Chef](https://www.chef.io/) – Ruby-based recipes & cookbooks.
- [Salt Project](https://saltproject.io/) – Event-driven CM & remote exec.
- [CFEngine](https://cfengine.com/) – Lightweight, scalable CM.
- [cloud-init](https://cloud-init.io/) – First-boot cloud instance config.

## Security & Firewalls

- [Fail2ban](http://www.fail2ban.org/) – Ban abusive IPs via logs.
- [Wazuh](https://wazuh.com/) – HIDS/SIEM (OSSEC-based).
- [Snort](https://www.snort.org/) – Network IDS/IPS.
- [Suricata](https://suricata.io/) – High-performance IDS/IPS/NSM.
- [ClamAV](https://www.clamav.net/) – Open-source antivirus.
- [HashiCorp Vault](https://www.vaultproject.io/) – Secrets management.
- [pfSense](https://www.pfsense.org/) – FreeBSD-based firewall/router.
- [OPNsense](https://opnsense.org/) – Modern FreeBSD firewall.
- [Certbot](https://certbot.eff.org/) – Let’s Encrypt certificates.
- [OpenSCAP](https://www.open-scap.org/) – Compliance & vulnerability scanning.

## Web Servers & Reverse Proxies

- [Apache HTTP Server](https://httpd.apache.org/) – Ubiquitous web server.
- [Nginx](https://nginx.org/) – High-perf web server & proxy.
- [Caddy](https://caddyserver.com/) – Automatic HTTPS by default.
- [Lighttpd](https://www.lighttpd.net/) – Lightweight web server.
- [Microsoft IIS](https://www.iis.net/) – Windows web server.
- [Apache Tomcat](https://tomcat.apache.org/) – Java Servlet/JSP container.
- [Node.js](https://nodejs.org/) / [Express](https://expressjs.com/) – JS runtime + web framework.

## Performance & Optimization

- [Varnish Cache](https://varnish-cache.org/) – HTTP accelerator/cache.
- [Memcached](https://memcached.org/) – Simple distributed cache.
- [Redis](https://redis.io/) – In-memory data store & cache.
- [Apache JMeter](https://jmeter.apache.org/) – Load testing.
- [Gatling](https://gatling.io/) – High-load testing with reports.
- [Locust](https://locust.io/) – Python-based load testing.
- [wrk](https://github.com/wg/wrk) – Modern HTTP benchmarking.
- [k6](https://k6.io/) – Scriptable load testing (OSS).

## Remote Access & Terminal Management

- [OpenSSH](https://www.openssh.com/) – Secure shell suite.
- [PuTTY](https://www.putty.org/) – SSH/Telnet client for Windows.
- [Mosh](https://mosh.org/) – Roaming, robust SSH alternative.
- [tmux](https://github.com/tmux/tmux) – Terminal multiplexer.
- [GNU Screen](https://www.gnu.org/software/screen/) – Terminal multiplexer.
- [Apache Guacamole](https://guacamole.apache.org/) – Clientless RDP/VNC/SSH in browser.
- [Remmina](https://remmina.org/) – Remote desktop client (Linux).
- [Teleport](https://goteleport.com/) – Unified access plane (SSH/K8s/DBs).
- [MeshCentral](https://meshcentral.com/) – Web-based remote management.
- [NoMachine](https://www.nomachine.com/) – High-perf remote desktop.

## Containers & Virtualization

- [Docker](https://www.docker.com/) – Standard container platform.
- [Docker Compose](https://docs.docker.com/compose/) – Multi-container apps.
- [Kubernetes](https://kubernetes.io/) – Container orchestration (CNCF).
- [Minikube](https://minikube.sigs.k8s.io/) / [Kind](https://kind.sigs.k8s.io/) – Local K8s.
- [Helm](https://helm.sh/) – K8s package manager.
- [Podman](https://podman.io/) – Daemonless/rootless containers.
- [LXC](https://linuxcontainers.org/lxc/) / [LXD](https://linuxcontainers.org/lxd/) – System containers.
- [KVM](https://www.linux-kvm.org/) – Linux hypervisor.
- [QEMU](https://www.qemu.org/) – Emulator/virtualizer.
- [VirtualBox](https://www.virtualbox.org/) – Desktop virtualization.
- [Proxmox VE](https://www.proxmox.com/en/proxmox-virtual-environment) – VM+container platform.
- [VMware vSphere](https://www.vmware.com/products/vsphere.html) – Enterprise virtualization.
- [XCP-ng](https://xcp-ng.org/) – Xen-based virtualization platform.
- [Nomad](https://www.nomadproject.io/) – Workload orchestrator (containers & more).
- [OpenStack](https://www.openstack.org/) – Private cloud IaaS.

## Serverless & Cloud Services

- **Functions / FaaS**
  - [AWS Lambda](https://aws.amazon.com/lambda/)
  - [Azure Functions](https://azure.microsoft.com/products/functions/)
  - [Google Cloud Functions](https://cloud.google.com/functions)
  - [Cloudflare Workers](https://workers.cloudflare.com/)
  - [OpenFaaS](https://www.openfaas.com/)
  - [Apache OpenWhisk](https://openwhisk.apache.org/)
  - [Serverless Framework](https://www.serverless.com/)

- **Platforms / PaaS**
  - [Heroku](https://www.heroku.com/)
  - [Netlify](https://www.netlify.com/)
  - [Vercel](https://vercel.com/)
  - [Firebase](https://firebase.google.com/)

- **Containers on Cloud**
  - [Amazon EKS](https://aws.amazon.com/eks/) / [ECS](https://aws.amazon.com/ecs/)
  - [Google Cloud Run](https://cloud.google.com/run)
  - [Azure Container Apps](https://azure.microsoft.com/products/container-apps/)
  - [AWS CDK](https://aws.amazon.com/cdk/) – IaC for AWS in code.

---

## Contributing

Pull requests are welcome! Please:
- Add one link per bullet, keep descriptions short, clear, and unbiased.
- Use the format: `[Name](link) – short description.`
- Ensure the project is actively maintained and relevant.
- Sort items alphabetically within each section when adding new entries.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)  
Released under **CC0 1.0** – do whatever you want with it.
