## JWT

### 1

JWT はアクセストークンをクライアント側で生成し、リクエストヘッダーに含めることで認証する仕組み

### 2

JWT は JSON 形式のデータを持つトークンのことである。
認証において使用される。
JWT は header と payload と signature の 3 つで構成されている。
header には、アルゴリズムと JWT の種類
payload には、認証情報、有効期限
signature は、header と payload を結合し暗号化したもの

JWT はサーバー側で生成される。
生成された JWT は暗号化され、クライアントにレスポンスとして返却される。
クライアント側からは返却された JWT を次のリクエストに含めることにより、サーバー側で signature の検証を行い改ざんが検知されていなければ正常に動作するようになっている。
もし、クライアント側で header または payload を改ざんしリクエストをすると、サーバー側の signature 検証の際に、改ざんが検知され、JWT の無効がエラーとして返される。

![image](https://github.com/user-attachments/assets/5c44bb26-e82f-4d3e-b5c2-126433de7ca4)
