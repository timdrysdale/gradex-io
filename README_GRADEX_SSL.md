sudo certbot certonly --manual -d '*.gradex.io'

log in to namecheap and update TXT record
wait one minute, then check here:

https://toolbox.googleapps.com/apps/dig/#TXT/

for server

_acme-challenge.gradex.io

If matches 

sudo systemctl restart nginx

Then check cert at https://pdf.gradex.io

Is there instantly after restart.
