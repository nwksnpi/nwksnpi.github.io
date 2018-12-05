# Pagesの挙動

## mdの解釈

- 各フォルダにreadme.mdが一つであればmdとして解釈され表示されるっぽい
- 他のmdがあるとうまく行かない、htmlがあるとそちらが優先される

## 画像の貼り方

<img src="gacha_cut.jpg" width="100">

~~~
imgタグならサイズ指定できる
<img src="gacha_cut.jpg" width="100">

mdだとサイズ指定が効かないのでやめた方が良い
![hoge](gacha_cut.jpg)
~~~

