## git config

- [x] `git config` で設定する情報はどこで確認できますか？  
→ git config --listで確認できる

- [x] `git config --global` と `git config --local` の違いは何ですか？  
→ グローバルはユーザー全体、ローカルはリポジトリ単位

- [x] `git config` を使って、Git のコミットに使用するメールアドレスを設定するコマンドは何ですか？  
→ git config --global user.email "メールアドレス"

- [x] Git の設定が保存されるファイルはどこにありますか？  
→ プロジェクトの隠しファイル内にある

- [x] `git config --list` で表示される情報は何ですか？  
→ gitの設定情報が確認できる。ユーザー名やメールアドレス

- [x] ユーザー情報をリポジトリ単位で設定したい場合、どのオプションを使用しますか？  
→ git config --local user.name "john"

- [ ] `git config` を使ってエディタを変更するコマンドは何ですか？  
→ ...
> **💡解説:**  
エディタを変更する場合、`git config` を使って `core.editor` 設定を変更できます。  
例えば、`git config --global core.editor "code --wait"` のように Visual Studio Code をエディタとして設定できます。

- [x] `git config --global` で設定した内容は、他のリポジトリでも使われますか？  
→ 使われます。

- [x] `git config` で設定する情報はどこで確認できますか？  
→ git config --list

- [x] `git config --global` と `git config --local` の設定が競合した場合、どちらが優先されますか？  
→ git config --localが優先される。
