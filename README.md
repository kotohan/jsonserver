# jsonserver
## これはなに
思いつきで作ったクソコード  
読めばわかるって言いたいけどカオスすぎて読むのつらそうなので解説するとモックサーバもどき  

## RESTなのにGET以外対応しない理由
GET以外のメソッドに利用されることを想定していないため。  

## known issue
- リファクタリングできてない、全メソッドmainべた書き。時間のあるときやります。プルリクも歓迎です。
- 現時点では動作が限定されてます。すぐ必要だった部分だけを実装しました。