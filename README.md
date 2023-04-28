# Ubuntu
## [SSH] ssh returns "Bad owner or permissions on ~/.ssh/config"
```
chmod 600 ~/.ssh/config
```

## [WEB-SERVER] solve www-data on nginx/php conf
```
sudo usermod -aG yoganugraha www-data
sudo usermod -aG www-data yoganugraha
id yoganugraha
groups yoganugraha
id www-data
groups www-data
```

## rsync
rsync -avL --progress -e "ssh -i ~/Documents/yoga.pem" ~/path-file-or-folder-to-copy ubuntu@xx.xxx.x.xxx:/path-folder-on-server

## certbot
sudo certbot --installer nginx --authenticator webroot -d app-yoga.34.220.1.94.sslip.io --webroot-path /home/ubuntu/app-yoga/