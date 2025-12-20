Problems faced:
- Nginx listening only on port 80
- Wrong site file being edited
- 403 Forbidden after HTTPS enabled

How they were solved:
- Used `nginx -T` to inspect active configuration
- Identified active site via `sites-enabled`
- Enabled port 443 with SSL
- Fixed file permissions and index file

Main lesson:
Configuration that is not loaded does not exist.
