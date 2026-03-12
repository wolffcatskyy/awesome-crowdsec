# Awesome CrowdSec [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<div align="center">
	<a href="https://crowdsec.net">
		<img src="media/crowdsec-logo.png" alt="CrowdSec" width="400">
	</a>
</div>

A curated list of awesome CrowdSec resources, bouncers, integrations, and tools.

[CrowdSec](https://crowdsec.net) is an open-source, crowd-powered security suite that detects and blocks malicious behavior using community-driven threat intelligence. Think Fail2Ban meets a global IP reputation network.

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

- [crowdsec](https://github.com/crowdsecurity/crowdsec) - The core detection engine that parses logs and applies behavioral scenarios.
- [CrowdSec Console](https://app.crowdsec.net) - Cloud console for fleet management, threat visualization, and CTI lookups.
- [crowdsec-docs](https://github.com/crowdsecurity/crowdsec-docs) - Source repository for the official documentation.
- [Documentation](https://docs.crowdsec.net) - Official documentation covering installation, configuration, and API usage.
- [hub](https://github.com/crowdsecurity/hub) - Community-maintained parsers, scenarios, and collections for various log sources.
- [sec-lists](https://github.com/crowdsecurity/sec-lists) - Curated keyword and pattern lists used by CrowdSec scenarios.

## Bouncers

### Firewall

- [crowdsec-unifi-bouncer](https://github.com/wolffcatskyy/crowdsec-unifi-bouncer) - Syncs CrowdSec decisions to UniFi firewalls via the UniFi API with Docker support.
- [cs-firewall-bouncer](https://github.com/crowdsecurity/cs-firewall-bouncer) - Official bouncer supporting iptables, nftables, ipset, and pf on Linux/BSD.
- [cs-firewall-bouncer-docker](https://github.com/shgew/cs-firewall-bouncer-docker) - Containerized version of the official firewall bouncer for Docker deployments.
- [cs-mikrotik-bouncer-alt](https://github.com/nvtkaszpir/cs-mikrotik-bouncer-alt) - Community MikroTik RouterOS bouncer using the REST API.
- [cs-windows-firewall-bouncer](https://github.com/crowdsecurity/cs-windows-firewall-bouncer) - Official bouncer that manages Windows Firewall rules.

### Web Servers & Proxies

- [caddy-crowdsec-bouncer](https://github.com/hslatman/caddy-crowdsec-bouncer) - Caddy module that blocks malicious traffic using CrowdSec decisions.
- [crowdsec-bouncer-traefik-plugin](https://github.com/maxlerebourg/crowdsec-bouncer-traefik-plugin) - Traefik middleware plugin with IP verification and WAF support.
- [cs-apache2-bouncer](https://github.com/crowdsecurity/cs-apache2-bouncer) - Official Apache HTTP Server bouncer using mod_lua.
- [cs-haproxy-bouncer](https://github.com/crowdsecurity/cs-haproxy-bouncer) - Official HAProxy bouncer using the Stream Processing Offload Engine.
- [cs-haproxy-spoa-bouncer](https://github.com/crowdsecurity/cs-haproxy-spoa-bouncer) - HAProxy SPOE filter with WAF capabilities and IP-based protection (beta).
- [cs-nginx-bouncer](https://github.com/crowdsecurity/cs-nginx-bouncer) - Official Nginx bouncer using Lua for request filtering.
- [cs-openresty-bouncer](https://github.com/crowdsecurity/cs-openresty-bouncer) - OpenResty/Nginx bouncer with native Lua integration.
- [envoy-proxy-crowdsec-bouncer](https://github.com/kdwils/envoy-proxy-crowdsec-bouncer) - Lightweight remediation component for Envoy proxy.
- [traefik-crowdsec-bouncer](https://github.com/fbonalair/traefik-crowdsec-bouncer) - Standalone HTTP verification service for Traefik forward auth.

### Cloud & CDN

- [cs-aws-waf-bouncer](https://github.com/crowdsecurity/cs-aws-waf-bouncer) - Official bouncer that manages AWS WAF IP sets across regions.
- [cs-cloudflare-bouncer](https://github.com/crowdsecurity/cs-cloudflare-bouncer) - Syncs decisions to Cloudflare IP lists with multi-account and multi-zone support.
- [cs-cloudflare-worker-bouncer](https://github.com/crowdsecurity/cs-cloudflare-worker-bouncer) - Edge-based bouncer using Cloudflare Workers for multi-zone setups.

### CMS & Applications

- [cs-standalone-php-bouncer](https://github.com/crowdsecurity/cs-standalone-php-bouncer) - Drop-in PHP bouncer for any PHP application without framework dependencies.
- [cs-wordpress-bouncer](https://github.com/crowdsecurity/cs-wordpress-bouncer) - WordPress plugin that blocks attackers or presents them with a captcha.
- [php-cs-bouncer](https://github.com/crowdsecurity/php-cs-bouncer) - PHP library for building custom bouncers in PHP applications.

### Other Bouncers

- [cs-custom-bouncer](https://github.com/crowdsecurity/cs-custom-bouncer) - Executes custom scripts on new or deleted CrowdSec decisions.

## Firewall Integrations

- [opnsense-plugin-crowdsec](https://github.com/crowdsecurity/opnsense-plugin-crowdsec) - OPNsense plugin for CrowdSec management via the web UI (archived).
- [pfSense-pkg-crowdsec](https://github.com/crowdsecurity/pfSense-pkg-crowdsec) - Native pfSense package with dashboard widget and firewall integration.

## Web UIs & Management

- [crowdsec-web-ui](https://github.com/TheDuffman85/crowdsec-web-ui) - Responsive web interface for browsing alerts, decisions, and machine status.
- [crowdsec_manager](https://github.com/hhftechnology/crowdsec_manager) - Full-featured management dashboard built with Go and React, with Pangolin integration.

## Blocklist & Threat Intelligence

- [crowdsec-abuseipdb-blocklist](https://github.com/goremykin/crowdsec-abuseipdb-blocklist) - Imports AbuseIPDB blocklists as CrowdSec decisions.
- [crowdsec-blocklist-import](https://github.com/wolffcatskyy/crowdsec-blocklist-import) - Imports 120k+ IPs from 36 free threat feeds into CrowdSec decisions.

## Docker Stacks & Examples

- [caddy-docker-proxy-crowdsec](https://github.com/kmobs/caddy-docker-proxy-crowdsec) - Caddy reverse proxy with automatic Docker service discovery and CrowdSec.
- [Docker-Traefik](https://github.com/SimpleHomelab/Docker-Traefik) - Production-ready media and home server stack with Traefik, CrowdSec, and OAuth2.
- [example-docker-compose](https://github.com/crowdsecurity/example-docker-compose) - Official reference Docker Compose configurations for common setups.
- [mediastack](https://github.com/geekau/mediastack) - Comprehensive Docker media stack with automated downloads and CrowdSec protection.
- [NPM-Crowdsec-Authentik-Stack](https://github.com/suckharder/NPM-Crowdsec-Authentik-Stack) - Nginx Proxy Manager with CrowdSec and Authentik SSO integration guide.
- [ServerSecurityStack](https://github.com/TenovanDigital/ServerSecurityStack) - Home server security stack combining Authelia, CrowdSec, Traefik, and Portainer.
- [Single-Stack](https://github.com/twoleftankles/Single-Stack) - All-in-one stack with Traefik, Authentik, CrowdSec, and Netbird VPN.
- [traefik-crowdsec-stack](https://github.com/psycho0verload/traefik-crowdsec-stack) - Step-by-step guide for deploying a Traefik and CrowdSec stack.

## Dashboards & Monitoring

- [grafana-dashboards](https://github.com/crowdsecurity/grafana-dashboards) - Official Grafana dashboards for visualizing CrowdSec metrics via Prometheus.

## SIEM & Security Operations

- [crowdsec-sentinel-playbook](https://github.com/crowdsecurity/crowdsec-sentinel-playbook) - Microsoft Sentinel playbook for automated IP reputation enrichment.
- [crowdsec-splunk-app](https://github.com/crowdsecurity/crowdsec-splunk-app) - Splunk app for ingesting and visualizing CrowdSec alerts and decisions.

## API Clients & SDKs

- [go-cs-bouncer](https://github.com/crowdsecurity/go-cs-bouncer) - Go library for building custom bouncers against the CrowdSec Local API.
- [nodejs-cs-bouncer](https://github.com/crowdsecurity/nodejs-cs-bouncer) - Node.js SDK for building bouncers and remediation components.

## Developer Tools

- [cs-log-replay-gui](https://github.com/crowdsecurity/cs-log-replay-gui) - Desktop GUI for replaying log files through CrowdSec scenarios for testing.

## Integrations

- [helm-charts](https://github.com/crowdsecurity/helm-charts) - Official Helm charts for deploying CrowdSec on Kubernetes.
- [home-assistant-addons](https://github.com/crowdsecurity/home-assistant-addons) - Home Assistant add-ons for running CrowdSec alongside home automation.
- [spksrc-crowdsec](https://github.com/crowdsecurity/spksrc-crowdsec) - Native Synology NAS package built with SynoCommunity spksrc.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

---

*List curation and project selection by the maintainer. AI tools used for formatting, lint compliance, and alphabetical ordering.*
