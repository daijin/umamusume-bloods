# umamusume-bloods

ウマ娘に登場するキャラクターたちの、史実における血統をメモする図です。

## コンセプト

* なんとなく登場キャラ同士の関係性が分かるようになると嬉しい。
* アニメなどの作中で「運命的な何かを感じます」って言ってたら、だいたい史実で何か血縁関係があるので、そこをちゃんと視認できるようにしたいなーと。

## 記述ルール

### 色塗り

* 育成ウマ娘として実装されたら<font color="red">赤枠</font>。
* 育成ウマ娘としては実装されていないが、[公式ポータルのキャラ紹介](https://umamusume.jp/character/)に登場するのであれば<font color="blue">青枠</font>。
* キャラ紹介に居なくても、アニメなどの作中に「この子、名前出てなかったり改変されてたりするけど、たぶんリアルのあの馬だよね」というのが分かれば、それも分かる範囲で載せる（例：レオダーバン）。<font color="blue">青枠</font>。

### 複雑度

* **図が複雑怪奇になって読みづらくならないように気をつける**。そのため、中間の親情報は適度に省略する（コメントアウトを活用）。
* 親は片親だけ書くでもOK。あくまでも**登場キャラ同士の関係性が分かりやすいこと**を主体とする。
* 登場キャラに辿り着いたら、そこから先は書かなくても良い。

## 図の操作

### Preview

* 拡張機能「Graphviz (dot) language support for Visual Studio Code」を導入する
* 導入後、 `.dot`ファイルを開いて `Ctrl + Shift + V` すれば、Previewしながら書ける

### Save

* Preview画面で「↓」ボタンから `.svg` ファイルが保存できる。
* 保存した `.svg` ファイルは、Edgeで開いて「Webキャプチャ」すればjpegで保存できる。

## License

MIT
