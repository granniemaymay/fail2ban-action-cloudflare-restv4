Fail2Ban Action Configuration for CloudFlare REST API V4
========================================================

Installation:

* Copy action.d/cloudflare-restv4.conf to your /etc/fail2ban/action.d directory.
* Get your CloudFlare Global API Key: https://dash.cloudflare.com/profile
* Modify your /etc/fail2ban/jail.local as shown in the sample jail.local file provided in this repository. Set cfemail and cfapikey to your cloudflare account email and Global API Key respectively.
* Restart Fail2Ban with: service fail2ban restart

More info: <https://www.kazimer.com/fail2ban-action-for-cloudflare-rest-api-v4/>
