# mobileHeight 

　innerHeight等のさまざまなブラウザのサイズを示す数値を確認するためのページです。

　[GitHubページ](https://taguchishuusei.github.io/mobileHeight/)



【きっかけ】

　横長の写真を表示するWebページをスマホで見ると、ブラウザの上下にアドレスバー等のバーが出て高さが小さくなって写真を大きく表示できない。
　こうした場合、ページを縦方向にスクロールさせるとバーが自動的に隠れるのでこれを利用したいが、このときinnerHeightなどがどう変化するのか確認したかった。



【動作】

　ボタンを押すことで window.innerHeight, window.outerHeight, document.body.clientHeight, document.documentElement.clientHeight などを取得して画面表示し、バーが表示されている状態と隠れた状態で比較できるよ。

【結果】

　試してみたところandroidのchrome, FireFox, safari でサイズの変化に違いがあった。
