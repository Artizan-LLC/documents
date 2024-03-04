### テストメール送信

```
Mail::raw('メール本文', function($message) { $message->to('atomuoku@gmail.com')->subject('メールタイトル'); });
```