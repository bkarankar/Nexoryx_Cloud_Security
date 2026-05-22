# Nexoryx_Cloud_Security

Production-ready cloud and Kubernetes security platform with Falco, Wazuh, Trivy, NGINX WAF, VPN automation, SSL/TLS hardening, IAM best practices, and centralized security monitoring.

## Features

- Kubernetes runtime security
- Falco threat detection
- Trivy container scanning
- Wazuh SIEM integration
- NGINX Web Application Firewall
- WireGuard VPN automation
- SSL/TLS hardening
- Kubernetes Network Policies
- Secrets management
- Security monitoring
- RBAC policies
- Production-ready manifests

## Stack

- Kubernetes
- Falco
- Trivy
- Wazuh
- NGINX
- WireGuard
- Prometheus
- Grafana

## Deployment

```bash
kubectl apply -f kubernetes/
```

## Namespace

```bash
nexoryx-security
```

## Components

- Falco
- Trivy
- Wazuh
- NGINX WAF
- WireGuard VPN
- Grafana
- Prometheus

## Notes

Update domains, TLS certificates, VPN keys, and secrets before production deployment.
