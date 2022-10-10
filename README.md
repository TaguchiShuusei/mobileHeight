# mobileHeight 

【疑問】
　横長の写真をスマホで表示しようとしたとき、ブラウザはアドレスバーなどのバーが表示されるため、縦の長さが成約を受けるがこれをできるだけ大きく表示されるようにした。
　ページを縦方向にスクロールさせるとバーが隠れるが、このときCSSや、Javascriptで認識するinnerHeightなどに変化があるのだろうか？

【検証方法】
　window.innerHeight, window.outerHeight, document.body.clientHeight, document.documentElement.clientHeight などを画面に表示できるページを作成し、バーが表示された状態と隠れた状態で比較できるようにした。
　実際にやってみたところ、androidのchrome, FireFox, safari でサイズの変化に違いがあった。
