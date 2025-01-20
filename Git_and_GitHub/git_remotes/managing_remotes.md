## リモート管理
- [x] `git remote add`のコマンドの役割は何ですか？  
→ リモートリポジトリを追加するコマンド

- [x] `git remote -v`で表示される情報にはどんなものがありますか？  
→ リモートリポジトリのURL

- [x] `git push`と`git pull`の違いは何ですか？  
→ pushはリポジトリへコミットをリモートリポジトリに通知する、pullはリモートリポジトリの情報をローカルに取得し、マージするコマンド

- [ ] リモートリポジトリから最新の変更を取得するにはどのコマンドを使用しますか？  
→ `git fetch origin <remote branch name>`
> **💡解説:**  
> `git fetch`コマンドを使用してリモートリポジトリから最新の変更を取得します。`git fetch origin <remote branch name>`という形式ではなく、`git fetch`だけでリモートリポジトリの変更を取得します。

- [x] `git fetch`と`git pull`の違いは何ですか？  
→ fetchは最新の変更を取得するだけでマージはしない。pullは取得し、マージまで行う
