---
layout: layouts/post.njk
title: About LIVIDnet
templateClass: tmpl-post
eleventyNavigation:
  key: About
  order: 2
---

LIVIDnet is a small, experimental computer network ("homelab") physically situated in Athens, Greece.

It serves as a side-project that is being maintained by [Panagiotis Vasilopoulos](https://alwayslivid.com/about) (in short, Panos, also known as "AlwaysLivid").

## Motivation

I'm running the network for the following reasons:

- I want to promote the right to privacy for the general population and make the internet safer.
- I want to endorse experimentation and assist people with ["self-hosting"](https://en.wikipedia.org/wiki/Self-hosting_(web_services)) their own services.
- I want to participate in creating solutions that will make peoples' lives easier.
- I want to learn and broaden my own skillset in the fields of network and system administration, as well as automation.

## Services

The following services are being hosted on the network:

- [dn42 node](https://dn42.dev) (`aut-num: 4242420799`)
- [Matrix homeserver](https://matrix.livid.pw)

### Currently offlien

- [Tor Relay](https://metrics.torproject.org/rs.html#details/1A7F1DDA2E4C41EE894F61168E80CCB6AB84D18D)
- [Mastodon](https://social.livid.pw)
- [NextCloud](https://cloud.livid.pw)
- Minecraft (dn42 IP: `172.20.34.168`)

Many of these instances are not currently open for registration by the general public in order to prevent abuse, but you can request access.

## Characteristics 

### Hardware

The network mostly consists of small single-board computers and old hardware.

- Raspberry Pi 4B+ (Model: `4B+`, OS: `Ubuntu 20.04`, RAM: `4 GB`)
- Raspberry Pi 4B+ (Model: `4B+`, OS: `Ubuntu 20.04`, RAM: `1 GB`)

#### Currently being upgraded/replaced

- Old Desktop (CPU: `Intel i3-3220`, OS: `Ubuntu 20.04`, RAM: `8 GB`)

### Software

- Web server: [Caddy](https://caddyserver.com/)
- SSL certificate management: [Certbot](https://certbot.eff.org/) 

### Additional notes

My systems are mostly managed automatically with the help of cronjobs and homebrewed software.
