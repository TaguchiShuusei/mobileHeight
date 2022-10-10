# mobileHeight 

【このページの概要】

　innerHeight等のさまざまなブラウザのサイズを示す数値を確認するためのページ。


【背景】

　横長の写真をスマホで表示しようとしたとき、ブラウザにはアドレスバー等のバーが表示されるため縦の長さが制約を受けるが写真はできるだけ大きく表示されるようにしたい。

　ページを縦方向にスクロールさせるとバーが隠れるが、このときCSSや、Javascriptで認識するinnerHeightなどに変化があるのだろうか？

　あるのであれば、それを使って写真をできるだけ大きく表示することができるのではないだろうか？


【検証方法】

　window.innerHeight, window.outerHeight, document.body.clientHeight, document.documentElement.clientHeight などを画面に表示できるページを作成し、バーが表示された状態と隠れた状態で比較できるようにした。

　実際にやってみたところ、androidのchrome, FireFox, safari でサイズの変化に違いがあった。

　[GitHubページ](https://taguchishuusei.github.io/mobileHeight/)