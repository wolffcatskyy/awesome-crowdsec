# Awesome CrowdSec [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

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
- [Integrations](#integrations)
- [Contributing](#contributing)

## Official Resources

- [crowdsec](https://github.com/crowdsecurity/crowdsec) - The main CrowdSec engine (12.5k stars)
- [crowdsec-docs](https://github.com/crowdsecurity/crowdsec-docs) - Official documentation (42 stars)
- [CrowdSec Console](https://app.crowdsec.net) - Cloud console and threat intelligence
- [Documentation](https://docs.crowdsec.net) - Official documentation website
- [hub](https://github.com/crowdsecurity/hub) - Official parsers and scenarios (221 stars)
- [sec-lists](https://github.com/crowdsecurity/sec-lists) - Keywords and patterns lists (16 stars)

## Bouncers

### Firewall

- [crowdsec-unifi-bouncer](https://github.com/wolffcatskyy/crowdsec-unifi-bouncer) - UniFi firewall integration via API (15 stars)
- [cs-firewall-bouncer](https://github.com/crowdsecurity/cs-firewall-bouncer) - Official firewall bouncer for iptables, nftables, ipset, pf (170 stars)
- [cs-firewall-bouncer-docker](https://github.com/shgew/cs-firewall-bouncer-docker) - Dockerized firewall bouncer (24 stars)
- [cs-mikrotik-bouncer](https://github.com/funkolab/cs-mikrotik-bouncer) - MikroTik RouterOS bouncer (65 stars)
- [cs-mikrotik-bouncer-alt](https://github.com/nvtkaszpir/cs-mikrotik-bouncer-alt) - Alternative MikroTik bouncer (22 stars)
- [cs-windows-firewall-bouncer](https://github.com/crowdsecurity/cs-windows-firewall-bouncer) - Windows Firewall bouncer (31 stars)

### Web Servers & Proxies

- [caddy-crowdsec-bouncer](https://github.com/hslatman/caddy-crowdsec-bouncer) - Caddy module for CrowdSec (331 stars)
- [crowdsec-bouncer-traefik-plugin](https://github.com/maxlerebourg/crowdsec-bouncer-traefik-plugin) - Traefik plugin for CrowdSec WAF (677 stars)
- [cs-haproxy-bouncer](https://github.com/crowdsecurity/cs-haproxy-bouncer) - Official HAProxy bouncer (31 stars)
- [cs-nginx-bouncer](https://github.com/crowdsecurity/cs-nginx-bouncer) - Official Nginx bouncer (59 stars)
- [cs-openresty-bouncer](https://github.com/crowdsecurity/cs-openresty-bouncer) - OpenResty bouncer (22 stars)
- [envoy-proxy-crowdsec-bouncer](https://github.com/kdwils/envoy-proxy-crowdsec-bouncer) - Envoy proxy bouncer (21 stars)
- [traefik-crowdsec-bouncer](https://github.com/fbonalair/traefik-crowdsec-bouncer) - HTTP bouncer for Traefik (325 stars)

### Cloud & CDN

- [cs-cloud-firewall-bouncer](https://github.com/crowdsecurity/cs-cloud-firewall-bouncer) - Cloud firewall bouncer (15 stars)
- [cs-cloudflare-bouncer](https://github.com/crowdsecurity/cs-cloudflare-bouncer) - Cloudflare bouncer with multi-account support (56 stars)

### CMS & Applications

- [cs-standalone-php-bouncer](https://github.com/crowdsecurity/cs-standalone-php-bouncer) - Standalone PHP bouncer (16 stars)
- [cs-wordpress-bouncer](https://github.com/crowdsecurity/cs-wordpress-bouncer) - WordPress plugin bouncer (43 stars)
- [php-cs-bouncer](https://github.com/crowdsecurity/php-cs-bouncer) - PHP bouncer library (17 stars)

### Other Bouncers

- [cs-custom-bouncer](https://github.com/crowdsecurity/cs-custom-bouncer) - Custom scripts bouncer (15 stars)

## Firewall Integrations

- [opnsense-plugin-crowdsec](https://github.com/crowdsecurity/opnsense-plugin-crowdsec) - OPNsense plugin (69 stars)
- [pfSense-pkg-crowdsec](https://github.com/crowdsecurity/pfSense-pkg-crowdsec) - pfSense package (72 stars)

## Web UIs & Management

- [crowdsec-dashboard](https://github.com/liberodark/crowdsec-dashboard) - Dashboard (25 stars)
- [crowdsec-web-ui](https://github.com/TheDuffman85/crowdsec-web-ui) - Modern web interface for alerts and decisions (103 stars)
- [crowdsec_manager](https://github.com/hhftechnology/crowdsec_manager) - Web management interface with Pangolin integration (265 stars)

## Blocklist & Threat Intelligence

- [crowdsec-abuseipdb-blocklist](https://github.com/goremykin/crowdsec-abuseipdb-blocklist) - AbuseIPDB blocklist integration (23 stars)
- [crowdsec-blocklist-import](https://github.com/wolffcatskyy/crowdsec-blocklist-import) - Import 120k+ IPs from 36 free threat feeds (167 stars)

## Docker Stacks & Examples

- [caddy-docker-proxy-crowdsec](https://github.com/kmobs/caddy-docker-proxy-crowdsec) - Caddy + Docker proxy + CrowdSec (17 stars)
- [Docker-Traefik](https://github.com/SimpleHomelab/Docker-Traefik) - Complete Docker media/home server with Traefik and CrowdSec (3414 stars)
- [example-docker-compose](https://github.com/crowdsecurity/example-docker-compose) - Official Docker Compose examples (203 stars)
- [mediastack](https://github.com/geekau/mediastack) - Ultimate Docker Compose media stack with CrowdSec (1654 stars)
- [NPM-Crowdsec-Authentik-Stack](https://github.com/suckharder/NPM-Crowdsec-Authentik-Stack) - NPM + CrowdSec + Authentik (35 stars)
- [ServerSecurityStack](https://github.com/TenovanDigital/ServerSecurityStack) - Security stack with Authelia, CrowdSec, Traefik (69 stars)
- [Single-Stack](https://github.com/twoleftankles/Single-Stack) - Traefik + Authentik + CrowdSec + Netbird (15 stars)
- [traefik-crowdsec-stack](https://github.com/psycho0verload/traefik-crowdsec-stack) - Complete Traefik-CrowdSec stack guide (91 stars)

## Dashboards & Monitoring

- [grafana-dashboards](https://github.com/crowdsecurity/grafana-dashboards) - Official Grafana dashboards for Prometheus (115 stars)

## Integrations

- [helm-charts](https://github.com/crowdsecurity/helm-charts) - Kubernetes Helm charts (41 stars)
- [home-assistant-addons](https://github.com/crowdsecurity/home-assistant-addons) - Home Assistant add-ons (90 stars)
- [nix-flake-crowdsec](https://github.com/kampka/nix-flake-crowdsec) - NixOS flake (32 stars)
- [spksrc-crowdsec](https://github.com/crowdsecurity/spksrc-crowdsec) - Synology package (17 stars)

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
