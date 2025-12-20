# Infra Lab – Nginx HTTPS (Self-Signed)

This project demonstrates the configuration of an Nginx web server with HTTPS
using a self-signed SSL certificate, commonly used in lab, staging, and internal
environments.

## What was implemented

* Nginx web server configuration
* HTTPS enabled on port 443
* HTTP (80) redirected to HTTPS
* Self-signed SSL certificate
* Manual troubleshooting of real issues (port binding, server blocks, 403 error)

## Why self-signed SSL

This project does not use a public domain.
Self-signed certificates are common in internal and lab environments
where trust is managed internally.

## Evidence

Screenshots and terminal outputs are available in the `docs/screenshots` directory.

## Key learnings

* Nginx server block precedence
* Active configuration vs edited configuration
* SSL does not replace HTTP (redirect is required)
* 403 errors related to permissions and index files

## Environment

* Ubuntu Server (VM)
* Nginx 1.24
