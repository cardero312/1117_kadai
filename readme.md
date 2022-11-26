# 賞味期限管理（進んだものの完成できず）



## 紹介と使い方

  ・食品入荷時の在庫一覧  
  ・賞味期限が近づいたものをお知らせしてくれる（予定）

  

## 工夫した点

 ・エクセルっぽい見た目で一覧としてみれて、かつ入力
  でき、保存できるように。    
 ・日付の入力を簡単にできるようにカレンダー形式に    
 ・開いた当日の日付

## 苦戦した点

  ・inputやtext-areaではなく、入力可能なものにするため
  そしてそれをlocal strageに保存できるようにするために
  想定以上に時間がかかりました。  
  ・カレンダー入力したものをlocal strageに保存するための
  コードがエラー続きでそこで足止め中  
  ・賞味期限から当日日付を引いて30日未満の商品なら商品情報をテキストエリアに表示して賞味期限が近いよ！というテキストも表示できるようにしたかったのだがここの数値計算のコードもうまく働かず・・・

## 参考にした web サイトなど
・contenteditable属性について
http://html5.cyberlab.info/global-attributes/contenteditable.html#:~:text=contenteditable%E5%B1%9E%E6%80%A7%E3%81%AF%E3%80%81%E8%A6%81%E7%B4%A0%E3%81%AE,%E7%B7%A8%E9%9B%86%E3%81%A7%E3%81%8D%E3%82%8B%E3%82%88%E3%81%86%E3%81%AB%E3%81%AA%E3%82%8B%E3%80%82

・tdタグの値取得について
https://qiita.com/Shiratsuki_Kurom/items/ecc9ff63519e0fb33941

・innerHTMLについて
https://wp-p.info/tpl_rep.php?cat=js-biginner&fl=r13
・カレンダー入力について
https://www.sejuku.net/blog/44165
・Val（）の取得について
https://www.sejuku.net/blog/45297?fbclid=IwAR1XWdglW4yH8sLF4NyCoavLEByBUmi0-kkgJBKvStRzTRxjvNGafiqrnb8