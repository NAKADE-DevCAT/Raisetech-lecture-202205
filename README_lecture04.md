---
# 第４回目講義について
---

### 1.　VPCの構成
* IP割り振り　：　192.168.0.0/16

### 2.　EC2とRDSの構成

__EC2__  
* OS : AmzonLinux2
* ホスト名：RTECH-WEB01  
* 追加パッケージ
   MySQL-Community-Client　：　Ver8.0.28
* 所属サブネット　：　パブリックサブネット（192.168.1.0/24）

__RDS__
* データベース　：　MySQL　：　Ver8.0.28
* 所属サブネット(サブネットグループ)
  : プライベートサブネットA（192.168.254.0/24）
  : プライベートサブネットB（192.168.253.0/24）

### 3.EC2からRDSへの接続

* EC2にインストールしたMySQLクライアントからの接続を実行。  
  接続を確認する。  

mysql -h (DBホスト名) -P (ポート番号：デフォルト3306） -u (ユーザー名：admin) -p (パスワード)  


実行結果  
  
[mnt_main01@rtech-web01 ~]$ mysql -h rtech-db01.cczxm8xtsdti.ap-northeast-1.rds.amazonaws.com -P 3306 -u admin -p  
Enter password:  
Welcome to the MySQL monitor.  Commands end with ; or \g.  
Your MySQL connection id is 21  
Server version: 8.0.28 Source distribution  

Copyright (c) 2000, 2022, Oracle and/or its affiliates.  

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.  

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.  

mysql>  
  
### 4.構成図  

* VSCodeのDraw.ioプラグインにて下記構成図を作成。


