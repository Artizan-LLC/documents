### 参考URL
https://reffect.co.jp/laravel/laravel-ubuntu-supervisor#supervisorctl
https://www.ibm.com/support/pages/%E5%8F%82%E8%80%83-rhel-%E4%B8%8A%E3%81%AE-supervisord-%E3%81%AE%E8%A8%AD%E5%AE%9A

### コマンド（スーパーバイザーの起動）
```
sudo service supervisord status
```
```
sudo service supervisord start
```
```
sudo service supervisord stop
```

### 設定の読み込み
```
sudo supervisorctl update 
```
```
sudo supervisorctl reread
```


### ubuntu
```
sudo service supervisor status
```
```
sudo supervisorctl reload
```

### プロセス確認
```
sudo supervisorctl status
```