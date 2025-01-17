## git init
- [x] git initを実行すると何が起こりますか？  
→ git initを実行したプロジェクトにGitリポジトリが初期化される。

- [x] git initを実行した後、どのディレクトリに何が作成されますか？  
→ プロジェクトに隠しディレクトリとして.gitが作成される。

- [x] git initを使って初期化したリポジトリにファイルを追加するには、次にどのコマンドを使いますか？  
→ git add 追加したいファイル

- [ ] git initを使って初期化したリポジトリを別のリモートリポジトリに接続するには、どのコマンドを使いますか？  
→ git remote リモートリポジトリ名
> **💡解説:**  
>  `git remote` はリモートリポジトリを管理するためのコマンドですが、リモートリポジトリの接続には `git remote add <name> <url>` を使用する必要があります。  
  例えば、`git remote add origin https://github.com/username/repo.git` といった形で設定します。

- [x] git initを実行したディレクトリで新しいブランチを作成するには、どのコマンドを使いますか？  
→ git switch -c develop
