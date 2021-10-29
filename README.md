# Clyde Smith dot calm
new photos go in /assets/images/portfolio and get up dated in /data/content.yml  
new momories get added directly to /data/content.yml  

to run locally `hugo server -D`  
to publish `hugo -D`  and then.  
`scp -i ~/.ssh/id_rsa.pub  -r public/* 154.16.118.55:/var/www/ClydeESmith.life/html/` from my local machine