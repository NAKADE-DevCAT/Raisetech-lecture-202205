***
# Raisetech  
# 第3回講義について
***
  
## <font color = "BLUE"> AP・DBサーバーについて </font>  
  
**・AP・DBサーバー情報**  
  
|内容|APサーバー|DBサーバー|
|:--|:--:|--:|
|サーバー名|PUMA（Rails）|MySQL|
|バージョン|Ver5.6.4(Ver6.1.3.1)|Ver8.0.29|
|バージョン確認コマンド|puma -v(rails -v)|mysql --version|
  
**・Railsの構成管理ツール　・・・　Bundler**  
  
### APサーバーの開始/停止

* 開始コマンド<br>
 bundle exec rails server -b 0.0.0.0
* 停止コマンド<br>
 Clou9コンソールでCtrl + C  
  ⇒　ブラウザでは「Oops」画面でアプリ表示できなくなる。  
  
### DBサーバーの開始/停止

* 開始コマンド  
 (sudo) service mysqld start
* 停止コマンド  
 (sudo) service mysqld stop  
 ⇒　ActiveRecordのエラー画面になりアプリ表示できない。  

***
## <font color = "GREEN"> 第3回講義振り返り </font>
***
  
1. アプリデプロイ時において、MySQLのdbcreateとmigrate処理を  
していなかった事に全く気付いていなかった。  
そのため、アプリが起動せずその原因を特定するのに時間がかかった。  
早めに質問するのも大事だし、冷静に講義動画見直して手順チェック徹底すべきと感じた。
2. インフラエンジニアとしてRubyアプリのフォルダ構成/ファイル構造を把握していきたい。  
その為にRubyチュートリアル等をもう少し深くやった方が良さそう。
3. 2と同様にMySQLのファイル構造も学習しておきたい。  
チューニング作業等にも関係してきそうなので。
4. どこかのタイミングでCLOUD9だけでなく、  
自分のPCにGITやRuby等の環境を構築してみる。
5. 仕事の関係上、自分のPCはWindowsがメインだが、Mac乗り換えも考える。
  
  