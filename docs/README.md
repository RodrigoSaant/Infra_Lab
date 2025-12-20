## Nginx HTTPS Configuration

Two server blocks were used:

- Port 80: redirect to HTTPS
- Port 443: SSL-enabled server

SSL was configured using a self-signed certificate
generated with OpenSSL.

This approach is commonly used in lab environments.
