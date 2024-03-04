### ステータス確認
```
sudo ufw status
```

### 設定
```
sudo ufw allow 80
```

### 再読み込み
```
sudo ufw reload
```

### 特定のポートを特定のIPアドレスのみ許可
```
sudo ufw allow from 64.18.0.0/20 to any port 3306
```

### ファイアウォールルールを表示
```
sudo ufw status	
```

### ファイアウォールルールの表示(ルール番号付き)
```
sudo ufw status numbered
```

### ファイアウォールルールの表示(詳細)
```
sudo ufw status verbose	
```

### ルール3番を削除
```
sudo ufw delete 3
```

### ルールを指定してファイアウォールルールを削除
```
sudo ufw delete allow 22/tcp
```

### ルールを指定してファイアウォールルールを削除
```
sudo ufw delete deny 23/tcp
```

### UFWを有効化
```
sudo ufw enable	
```

### UFWを無効化
```
sudo ufw disable
```

### UFWの無効化とデフォルトへのリセット
```
sudo ufw reset
```

