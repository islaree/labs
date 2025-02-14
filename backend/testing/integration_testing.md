## 統合テスト
- [x] 統合テストの目的は何ですか？その目的を説明してください。
> モジュールやコンポーネントを組み合わせた際に発生するエラーを発見するためのもの
- [x] 統合テストと単体テストの違いをどのように説明しますか？
> 単体テストはモジュールやコンポーネント単体だが、統合テストはそれらを組み合わせた際に正常に動作するかをテストする

- [x] 統合テストが必要になるのはどのような場面だと思いますか？
> ログインフォームからログインを行い、ログインAPIが呼び出され、リクエストが帰ってきて、その結果がセッションに保存され、アプリケーションを使用できるなど

- [x] 統合テストで一般的に使用される手法を1つ挙げ、その手法の概要を説明してください。
> トップダウンアプローチ：モジュールの組み合わせが大きいものから小さい組み合わせをチェックしていく方法

- [x] 統合テストで「モック」や「スタブ」が使われるのはなぜですか？
> 動作確認ように、仮のデータを静的に用意したりすること。例えば、テーブルにDBからのデータが表示されるが、テーブルのソート機能などを確認するためダミーのデータで確認する

- [x] 統合テストの対象として適切なシナリオを1つ提案してください。
> ログインフォームからログインを行い、ログインAPIが呼び出され、リクエストが帰ってきて、その結果がセッションに保存され、アプリケーションを使用できるなど

- [x] 統合テストが失敗した場合、最初に確認するべきことは何ですか？
> 失敗した箇所を確認する
