# JavaScript でSPARQL処理の基礎演習
## 演習１：Ex1.htmlを実行して動作を確認する
1.そのまま実行して動作を確認  

2.「結果を整形して表示」の関数（41-43行目）を切り替えて試す  
 - result_table(d.results.bindings);  
 - result_show(d.results.bindings);  
 - result_show2(d.results.bindings);  
 
3.「結果をJSON形式でフォームに表示」（46-47行目）のコメントを外して，結果のデータ形式を確認   
→下記の「JSONの整形ツール」を使うとよい  

4. 2.と3.の結果を見比べて，結果の整形方法を理解する  

## 演習２：Ex1.htmlを変更して好みのクエリ結果を表示できるようにする
1. クエリを変更して，好みの出力をできるようにする  
 - WikidataのSPARQLクエリ  
 - Wikidata以外のSPARQLエンドポイントを用いたクエリ  
 のそれぞれを試す．

2. 結果の表示方法を変更してみる  
→新しいresult_show(d.results.bindings) 関数を作り，HTMLやJavaScriptで表示方法を指定すればよい．  
 
## 演習３：クエリの一部をフォームやリストから入力できるようにする   
1. Ex2.html(クエリの一部をフォームに入力したキーワードで変更できる)サンプルを実行してみる  

2. Ex2.htmlのクエリを変更して試す．

3. 入力方法をフォーム以外（リストなど）に変更してみる

## 演習４：簡単な検索アプリの作成
演習１～３の内容をもとに，簡単な検索アプリを作成する

## 参考情報
### JSONの整形ツール
https://tools.m-bsys.com/development_tooles/json-beautifier.php

### JavaScript のデバッグ方法
https://ics.media/entry/190517/
