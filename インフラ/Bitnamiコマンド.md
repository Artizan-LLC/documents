### ルートディレクトリ
```
/opt/bitnami/apache2/htdocs
```


### Apache設定ファイル
```
/opt/bitnami/apache2/conf/bitnami/bitnami.conf
```
```
/opt/bitnami/apache2/conf/bitnami/bitnami-ssl.conf
```

### MySQLなどの初期パスワードが記載されたファイル
```
/home/bitnami/bitnami_application_password
```

### Apache
```
sudo /opt/bitnami/ctlscript.sh status apache
```
```
sudo /opt/bitnami/ctlscript.sh restart apache
```
```
sudo /opt/bitnami/ctlscript.sh start mariadb
```
```
sudo /opt/bitnami/ctlscript.sh status mariadb
```
```
sudo /opt/bitnami/ctlscript.sh stop mysql
```
