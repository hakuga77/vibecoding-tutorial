# Codex App セットアップ手順

勉強会の当日までに、以下の準備を完了させておいてください。

---

## 事前準備チェックリスト

- [ ] GitHub アカウントの作成
- [ ] Git のインストール（Windows）
- [ ] OpenAI Codex App のインストール
- [ ] このリポジトリの Clone

---

## STEP 1: GitHub アカウントを作成する

1. [https://github.com](https://github.com) にアクセスする
2. 「Sign up」をクリックしてアカウントを作成する
3. メールアドレス・パスワードを設定して登録を完了する

> すでに GitHub アカウントをお持ちの方はこのステップをスキップしてください。

---

## STEP 2: Git をインストールする（Windows）

1. [https://git-scm.com/download/win](https://git-scm.com/download/win) にアクセスする
2. 「Click here to download」をクリックしてダウンロードする
3. ダウンロードしたファイルをダブルクリックしてインストールする
4. インストール途中の設定はすべてデフォルト（そのまま Next）で OK

インストール確認：
- スタートメニューから「Git Bash」を開く
- `git --version` と入力して Enter → バージョン番号が表示されれば OK

---

## STEP 3: OpenAI Codex App をインストールする

1. OpenAI のサイトから Codex App の Windows 版をダウンロードする
2. ダウンロードしたインストーラーを実行する
3. 起動したら OpenAI アカウントでログインする

> OpenAI アカウントをお持ちでない方は、先にアカウントを作成してください。

---

## STEP 4: このリポジトリを Clone する

### Git Bash を使う場合

1. スタートメニューから「Git Bash」を開く
2. 以下のコマンドを入力して Enter

```bash
git clone https://github.com/YOUR_USERNAME/vibecoding-tutorial.git
```

3. `vibecoding-tutorial` フォルダが作成されれば成功

### Codex App から直接 Clone する場合

Codex App に「GitHub からリポジトリを Clone する方法」を聞いてみましょう。

---

## STEP 5: アプリが動くか確認する

1. Clone した `vibecoding-tutorial` フォルダを開く
2. `starter-app` フォルダの中にある `index.html` をダブルクリックする
3. ブラウザが開いて「出張プランナー」の画面が表示されれば OK ✅

---

## STEP 6: Codex App でフォルダを開く

1. Codex App を起動する
2. 「フォルダを開く」や「リポジトリを開く」の機能で `vibecoding-tutorial` フォルダを選択する
3. Codex App がフォルダを認識したら準備完了

---

## 困ったときは

当日ファシリテーターがサポートします。うまくいかない場合は遠慮なく声をかけてください。

次のステップ → [`03-hands-on-guide.md`](03-hands-on-guide.md)
