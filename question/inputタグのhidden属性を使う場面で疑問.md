## 情報を入力しない（前のページで入力させている）ページでpostの中身が入っていると証明させるのになぜinput type="hidden"を入れるのかわからない　　

会員登録の確認画面で確認させてから登録させるという処理の中でふと疑問に感じた

```
<form method="post" action="">

  <input type="hidden" name="action" value="submit">
  <input type="submit">
```
