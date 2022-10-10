# mobileHeight 

　innerHeight等のさまざまなブラウザのサイズを示す数値を確認するためのページです。

　[GitHubページ](https://taguchishuusei.github.io/mobileHeight/)


【きっかけ】

　横長の写真をスマホで表示するWebページを作成しようとしたとき、ブラウザの上下にアドレスバー等のバーが表示され縦の長さが小さくなって写真を大きく表示することができない。

　ページを縦方向にスクロールさせるとバーが隠れるのでこれを利用したいが、このときJavascriptで認識できるinnerHeightなどの数値に変化はあるのか確認したかった。



【動作】

　ボタンを押すことで window.innerHeight, window.outerHeight, document.body.clientHeight, document.documentElement.clientHeight などを取得して画面表示し、バーが表示されている状態と隠れた状態で比較できるようにしている。

【結果】

　いくつかのブラウザで試してみたところ、androidのchrome, FireFox, safari でサイズの変化に違いがあった。
