# トップページの商品６点を、１カ月の売上順にする

- トップページの商品6点を、現在は新しい順で表示していましたが、売上金額順にします。
- 計算方法
  - 本システムでは、１回の注文で１商品しか注文できない特性を利用します。
  - product_idで group by して、totalの金額が大きい順に出力します。
  - もし同じ金額の場合は、product_idの降順にします。
- この計算を、毎回実施するのは処理コストがかかるので、キャッシュして、１日１回（２４時間経過後に更新）としましょう。  

よろしくお願いいたします。

---

[<<一覧に戻る](../../ISSUES.md)