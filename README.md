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