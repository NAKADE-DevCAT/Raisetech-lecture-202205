---
# 第5回目講義について
---

### 1.　インフラ構成図
*下記構成図参照  
![構成図](./images/lecture05_kouseizu.png "kouseizu")

### 2.　検証環境接続

* 正常動作確認  
![正常系01](./images/lecture05_kenshou_OK_01.png "kenshouseijou01")  
![正常系02](./images/lecture05_kenshou_OK_01.png "kenshouseijou02")  
  
* <font color="red">異常系動作確認</font>  
![異常系01](./images/lecture05_kenshou_NG_01.png "kenshouijou01")  
![異常系02](./images/lecture05_kenshou_NG_02.png "kenshouijou02")  

### 3.本番環境接続

* 正常動作確認  
![正常系01](./images/lecture05_honban_OK_01.png "honbanseijou01")  
![正常系02](./images/lecture05_honban_OK_02.png "honbanseijou02")  

* <font color="red">異常系動作確認</font>  
**1台が停止しても問題なく接続可能**  
![異常系01](./images/lecture05_honban_NG_01.png "honbanijou01")  
![異常系02](./images/lecture05_honban_NG_02.png "honbanijou02")  

### 4.S3の扱い

**今回は静的サイトホスティングを利用して静的サイトを持たせる。**  
  この静的サイトにアクセスすると、  
  本来の本番用サイトにリダイレクトする
  
### 第5回目の学び

1. やはりアプリ面の学習も必要に感じた。  
サーバー側が構築できてもアプリ側のエラーで止まってしまうことがあった。  
2. ログにはしっかり情報が主t力されているので、  
確認はしっかりした方が良い。
3.　Windows系が多かったので、Linuxに早く慣れたい。