# Awesome CrowdSec [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<div align="center">
	<a href="https://crowdsec.net">
		<img src="media/crowdsec-logo.png" alt="CrowdSec" width="400">
	</a>
</div>

A curated list of awesome CrowdSec resources, bouncers, integrations, and tools.

[CrowdSec](https://crowdsec.net) is an open-source and collaborative security stack that analyzes behaviors and responds to attacks.

## Contents

- [Official Resources](#official-resources)
- [Bouncers](#bouncers)
  - [Firewall](#firewall)
  - [Web Servers & Proxies](#web-servers--proxies)
  - [Cloud & CDN](#cloud--cdn)
  - [CMS & Applications](#cms--applications)
  - [Other Bouncers](#other-bouncers)
- [Firewall Integrations](#firewall-integrations)
- [Web UIs & Management](#web-uis--management)
- [Blocklist & Threat Intelligence](#blocklist--threat-intelligence)
- [Docker Stacks & Examples](#docker-stacks--examples)
- [Dashboards & Monitoring](#dashboards--monitoring)
- [SIEM & Security Operations](#siem--security-operations)
- [API Clients & SDKs](#api-clients--sdks)
- [Developer Tools](#developer-tools)
- [Integrations](#integrations)

## Official Resources

- [crowdsec](https://github.com/crowdsecurity/crowdsec) - The main CrowdSec engine.
- [CrowdSec Console](https://app.crowdsec.net) - Cloud console and threat intelligence.
- [crowdsec-docs](https://github.com/crowdsecurity/crowdsec-docs) - Official documentation.
- [Documentation](https://docs.crowdsec.net) - Official documentation website.
- [hub](https://github.com/crowdsecurity/hub) - Official parsers and scenarios.
- [sec-lists](https://github.com/crowdsecurity/sec-lists) - Keywords and patterns lists.

## Bouncers

### Firewall

- [crowdsec-unifi-bouncer](https://github.com/wolffcatskyy/crowdsec-unifi-bouncer) - UniFi firewall integration via API.
- [cs-firewall-bouncer](https://github.com/crowdsecurity/cs-firewall-bouncer) - Official firewall bouncer for iptables, nftables, ipset, pf.
- [cs-firewall-bouncer-docker](https://github.com/shgew/cs-firewall-bouncer-docker) - Dockerized firewall bouncer.
- [cs-mikrotik-bouncer-alt](https://github.com/nvtkaszpir/cs-mikrotik-bouncer-alt) - Alternative MikroTik bouncer.
- [cs-windows-firewall-bouncer](https://github.com/crowdsecurity/cs-windows-firewall-bouncer) - Windows Firewall bouncer.

### Web Servers & Proxies

- [caddy-crowdsec-bouncer](https://github.com/hslatman/caddy-crowdsec-bouncer) - Caddy module for CrowdSec.
- [crowdsec-bouncer-traefik-plugin](https://github.com/maxlerebourg/crowdsec-bouncer-traefik-plugin) - Traefik plugin for CrowdSec WAF.
- [cs-apache2-bouncer](https://github.com/crowdsecurity/cs-apache2-bouncer) - Official Apache HTTP Server bouncer.
- [cs-haproxy-spoa-bouncer](https://github.com/crowdsecurity/cs-haproxy-spoa-bouncer) - HAProxy SPOE filter for CrowdSec with WAF and IP protection.
- [cs-nginx-bouncer](https://github.com/crowdsecurity/cs-nginx-bouncer) - Official Nginx bouncer.
- [cs-openresty-bouncer](https://github.com/crowdsecurity/cs-openresty-bouncer) - OpenResty bouncer.
- [envoy-proxy-crowdsec-bouncer](https://github.com/kdwils/envoy-proxy-crowdsec-bouncer) - Envoy proxy bouncer.

### Cloud & CDN

- [cs-aws-waf-bouncer](https://github.com/crowdsecurity/cs-aws-waf-bouncer) - Official AWS WAF bouncer.
- [cs-cloudflare-bouncer](https://github.com/crowdsecurity/cs-cloudflare-bouncer) - Cloudflare bouncer with multi-account support.
- [cs-cloudflare-worker-bouncer](https://github.com/crowdsecurity/cs-cloudflare-worker-bouncer) - Cloudflare Workers bouncer for multi-zone setups.

### CMS & Applications

- [cs-standalone-php-bouncer](https://github.com/crowdsecurity/cs-standalone-php-bouncer) - Standalone PHP bouncer.
- [cs-wordpress-bouncer](https://github.com/crowdsecurity/cs-wordpress-bouncer) - WordPress plugin bouncer.
- [php-cs-bouncer](https://github.com/crowdsecurity/php-cs-bouncer) - PHP bouncer library.

### Other Bouncers

- [cs-custom-bouncer](https://github.com/crowdsecurity/cs-custom-bouncer) - Custom scripts bouncer.

## Firewall Integrations

- [opnsense-plugin-crowdsec](https://github.com/crowdsecurity/opnsense-plugin-crowdsec) - OPNsense plugin.
- [pfSense-pkg-crowdsec](https://github.com/crowdsecurity/pfSense-pkg-crowdsec) - Package for pfSense firewall integration.

## Web UIs & Management

- [crowdsec-web-ui](https://github.com/TheDuffman85/crowdsec-web-ui) - Modern web interface for alerts and decisions.
- [crowdsec_manager](https://github.com/hhftechnology/crowdsec_manager) - Web management interface with Pangolin integration.

## Blocklist & Threat Intelligence

- [crowdsec-abuseipdb-blocklist](https://github.com/goremykin/crowdsec-abuseipdb-blocklist) - AbuseIPDB blocklist integration.
- [crowdsec-blocklist-import](https://github.com/wolffcatskyy/crowdsec-blocklist-import) - Import 120k+ IPs from 36 free threat feeds.

## Docker Stacks & Examples

- [caddy-docker-proxy-crowdsec](https://github.com/kmobs/caddy-docker-proxy-crowdsec) - Caddy + Docker proxy + CrowdSec.
- [Docker-Traefik](https://github.com/SimpleHomelab/Docker-Traefik) - Complete Docker media/home server with Traefik and CrowdSec.
- [example-docker-compose](https://github.com/crowdsecurity/example-docker-compose) - Official Docker Compose examples.
- [mediastack](https://github.com/geekau/mediastack) - Ultimate Docker Compose media stack with CrowdSec.
- [NPM-Crowdsec-Authentik-Stack](https://github.com/suckharder/NPM-Crowdsec-Authentik-Stack) - NPM + CrowdSec + Authentik.
- [ServerSecurityStack](https://github.com/TenovanDigital/ServerSecurityStack) - Security stack with Authelia, CrowdSec, Traefik.
- [Single-Stack](https://github.com/twoleftankles/Single-Stack) - Traefik + Authentik + CrowdSec + Netbird.
- [traefik-crowdsec-stack](https://github.com/psycho0verload/traefik-crowdsec-stack) - Complete Traefik-CrowdSec stack guide.

## Dashboards & Monitoring

- [grafana-dashboards](https://github.com/crowdsecurity/grafana-dashboards) - Official Grafana dashboards for Prometheus.

## SIEM & Security Operations

- [crowdsec-sentinel-playbook](https://github.com/crowdsecurity/crowdsec-sentinel-playbook) - Microsoft Sentinel IP reputation playbook.
- [crowdsec-splunk-app](https://github.com/crowdsecurity/crowdsec-splunk-app) - Splunk app for CrowdSec integration.

## API Clients & SDKs

- [go-cs-bouncer](https://github.com/crowdsecurity/go-cs-bouncer) - Go library for the CrowdSec API.
- [nodejs-cs-bouncer](https://github.com/crowdsecurity/nodejs-cs-bouncer) - Official Node.js bouncer and remediation component.

## Developer Tools

- [cs-log-replay-gui](https://github.com/crowdsecurity/cs-log-replay-gui) - GUI for replaying logs through CrowdSec scenarios.

## Integrations

- [helm-charts](https://github.com/crowdsecurity/helm-charts) - Kubernetes Helm charts.
- [home-assistant-addons](https://github.com/crowdsecurity/home-assistant-addons) - Home Assistant add-ons.
- [spksrc-crowdsec](https://github.com/crowdsecurity/spksrc-crowdsec) - Synology package.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

---

*List curation and project selection by the maintainer. AI tools used for formatting, lint compliance, and alphabetical ordering.*
