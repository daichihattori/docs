前提
インスタンスは作ってある。そのインスタンスのグローバルipにhttp接続するとホームページが見える。elastic ip（静的ip）を導入している

1. freenomでドメイン発行
2. Route53でサブドメインを作成,freenomへ登録
3. ACMからの証明書発行
4. ALB作成

## freenomでドメインを発行する
ht

参考ページ
https://recipe.kc-cloud.jp/archives/11084
<-ほとんどこれ
https://blog.serverworks.co.jp/delegate-route53
<-freenomドメインの委任のみ参考