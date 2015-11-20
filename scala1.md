# scala1  

﻿** android開発でscalaむずかしい...？**  
-> ゲームなら現状unityが無難ぽい(iPhoneとAndoroid両対応できるから)  

scala->TASTY->JSとかバイトコード  

再帰は使うかどうか（スタック伸びまくり問題）  
モジュール分け -> 処理が追いにくくなるので意外と使わないことも  
末尾再帰 ＝ 関数の返し値が自分自身になる（≒最後にだけ自分を呼ぶ）  

ツリー構造は再帰でかこう  

scalaは省略しまくりだから読みにくい...?  
-> scala側で予測してくれている(implicit)  

カリー化つかうメリットないかも -> 再帰つかおう  

## **カリー化**  
- 『2引数以上の関数を、1引数の関数の定義だけで同じ機能を持つように定義を書き換えること』  
- [詳しい解説](http://qiita.com/KDKTN/items/6a27c0e8efa66b1f7799)

## **型パラメータ**  
- 型変数＝javaでいうジェネリックス  
- クラス定義のときに抽象的に定義できる  
- インスタンス化するときに **型縛り** できる  

## **ネスト**  
classやメソッドの中で定義すること（≒入れ子）  

-------------------------   


## **あとがき**
- sbt consoleコマンドでterminal上でscalaかけるっぽい（というかメソッドテスト的な）  

- Twitterで　#fpscal 検索すると様子がわかるので、興味ある人はぜひ  

- [名著ぽいもの（買った）](http://www.amazon.co.jp/Scala%E9%96%A2%E6%95%B0%E5%9E%8B%E3%83%87%E3%82%B6%E3%82%A4%E3%83%B3-%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0%E2%80%95Scalaz%E3%82%B3%E3%83%B3%E3%83%88%E3%83%AA%E3%83%93%E3%83%A5%E3%83%BC%E3%82%BF%E3%83%BC%E3%81%AB%E3%82%88%E3%82%8B%E9%96%A2%E6%95%B0%E5%9E%8B%E5%BE%B9%E5%BA%95%E3%82%AC%E3%82%A4%E3%83%89-Paul-Chiusano-ebook/dp/B00WM54V5Q/ref=sr_1_2?ie=UTF8&qid=1447846079&sr=8-2&keywords=scala)

- [参加年齢層に"ウケていた"エディタ](https://ja.wikipedia.org/wiki/Ed)  
- [scala勉強でよさげなサイト（java使い専用）](http://www.ne.jp/asahi/hishidama/home/tech/scala/def.html)  


- フレームワークまわりの豆知識  
> - Inputにcaptureつければスマホのカメラロールが立ち上がるようになる  
> - React.jsすごい  
