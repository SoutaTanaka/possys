# possysの使い方
## 新規登録の方法
- 「4.ユーザー登録」からユーザー登録をします。
			このとき，ユーザー名，Eメールアドレス，パスワードを入力する必要があります。
			パスワードはSHA256でハッシュされて保存されます。

- 「5.NFCカード登録」からNFCカードを登録します。
			 このとき，ユーザー名とパスワードを入力する必要があります。合っていた場合，NFCカードをNFCマークの上に置くことで，ユーザーとNFCカードを結びつけることができます。

## 購入/入金方法
- 「1.購入」から購入できます。
			NFCカードを置き，購入金額を入力してください。

- 「2.入金」から入金できます。
			 NFCカードを置き，入金金額を入力してください。
			 必ず，入金してから操作を行って下さい。

- possysでは，購入時に残高がマイナスになることを許容していますが，会計から任意のタイミングで徴収されても返せる額にとどめてください。

## 残高照会
- 「3.残高照会」から残高照会をすることができます。
			NFCカードを置くだけで照会できます。

## その他
### モード選択を間違えたら？
		Ctrl+ZでPythonを終了して，python3 possys_main.py とターミナルに入力してください。

### ログはどこで見れる？
		Slackに #possys_logチャンネルがあります。そこに入力されます。

### なんかエラーが置きた
		Slackの #possysでバグ報告してください。
