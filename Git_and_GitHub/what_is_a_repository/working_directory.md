## 作業ディレクトリ
- [x] GitのWorking Directoryとは何ですか？  
→ Gitで管理されているプロジェクトのローカルコピー  
- [x] Working Directoryでの変更は、Gitにどのように反映されますか？  
→ ステージングエリアに追加し、コミットすることでGitリポジトリに追加される。  
- [x] Working Directoryとステージングエリア（インデックス）の違いは何ですか？  
→ 変更をコミットする準備が整ったファイルが一時的に保存される場所  
- [x] Working Directoryの内容をGitに反映させるためにはどうすればよいですか？  
→ ステージングエリアに追加し、コミットすることでGitリポジトリに追加される。  
- [x] Gitでファイルの変更を取り消す方法はありますか？  
→ git reset コミット名 または git reset ステージング名  
- [ ] GitのWorking Directoryを他のブランチに切り替えた場合、どうなりますか？  
→ 切り替えた場合、ステージングしていない場合は消えてしまう。  
> **💡解説:**  
  変更がステージングされていない場合、ブランチを切り替えようとすると、その変更内容は作業中のブランチで失われます。Gitは、作業中の変更がブランチ切り替えと競合する可能性があるため、ステージングされていない変更を一時的に保存する方法（`git stash`）を使用することをお勧めします。  
  ステージングしていない変更がない場合、ブランチを切り替えることは問題ありません。
