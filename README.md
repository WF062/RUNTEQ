# READ　ME


■サービス概要
物語やゲーム等の登場人物・概要について簡単にwebサイトのようなものを作成できるツール。
同人作品における作品の魅力を伝えるために、個人の趣味でウェブサイトを作成したい方が数多くいるが、一から作るのが難しいため、
内容の入力をするだけで簡単に魅力あるキャラ紹介サイトを作れるようなサービスを作成してみたい。

■ このサービスへの思い・作りたい理由
趣味でクトゥルフ神話TRPGやマーダーミステリーといった、特定のキャラクターを演じながら物語体験をする遊びをしています。
マーダーミステリー作品は、販売サイトにて売り出されていますが、購入の決め手の一部となるのが、「キャラクターの魅力」です。
販売ページのPDF一枚にそれを収めるのではなく、特設のサイトがあればいいなと日頃感じています。
（普段遊んでいる仲間内からも多く「そういったツールがあると嬉しい」と言った意見を受けて、さらに強く感じました）
また、自身のキャラクターを自分で創造するTRPGという分野において、自分のキャラクターの魅力を最大限に伝えたいと言う人は多く、
自身でwixなどを利用して専用webサイトを作成される方もいますが、技術的や時間的に厳しいという方も多いです。
簡単にキャラ紹介サイトを作成できるツールは、そう言った方達に魅力的に見えると思います。
また、そういったニッチな遊びだけでなく、個人作成のゲームでのキャラクター紹介ページにも使用していただけるような作りにすれば、
ユーザーも増えやすいかと思っています。

■ ユーザー層について
個人の創作者（上記のようなTRPGプレイヤー、あるいは自分で小説・漫画を描いている方、自作ゲームを作られている方）
自分のコンテンツを広めてもらう、と言うような目的で作成したいので、このようなターゲット層になっています。

■サービスの利用イメージ
このサービスを利用することで、webサイト知識がない方でも、ある程度見栄えの良いキャラクター紹介サイトが、手軽で簡単に、短い時間で作成できるようになります。

■ ユーザーの獲得について
創作者はSNSでの情報収集・発信を多く行なっていることから、Xをメインとして広げたいと思っています
（X内での仲間から広がればいいなと思っています）

■ サービスの差別化ポイント・推しポイント
最近、サンリオからcharaforio(https://charaforio.com/ja)というサービスが発信されました、それに近しいかと思います。
差別点としては、キャラフォリオは「創作者自身」に焦点を当てていて、権利問題を重視したものになっていますし、創作者のポートフォリオといった側面が強いです。
それに対して、私が作りたいものは「創作品」に焦点を当てたいと思っています。あくまでも作った人物というよりも、創作したものの魅力が大きく伝わるようなつくりにしたいと考えています。
→ユーザーページから見たとき等に、ユーザー情報より、創作物が見やすいようにしたいと思っています。
 自身のことより、自分の作ったものをたくさん見て欲しい！と思っている方も多くいると思っているので、創作物の表示領域を大きくしたい、といった意味合いになります。
また、画像のAI生成の防止と、サイト上から画像をダウンロードできない仕組みを導入したいなと思っています。
→画像のAI生成の防止については、noai・noimageaiを使って学習拒否ができる旨を少し調べていますので、そちらを試したいと思っています。
サイト上から画像ダウンロードできない仕組みとして、右クリックの禁止を導入したいと思います（JSで出来ない仕組みがあると調べましたので、試してみたいと思っています）
 （これだけでは弱いと思ったので追記↓）
あとは、一つの「完成形」の画像を設定して（差替可能）、それに付随して制作過程をアップできるような仕組みを作成したいです。(タグ機能の応用みたいな感じでできるかなと思っています)
そうすれば、雑多に画像をただポンポンと投げるサイトではなく、綺麗なサイトの見た目を維持しつつ、細かな進捗を見て欲しいという肩の要望にも応えられると思っています。
（同人や個人の趣味の側面が大きいサイトなので、そういった過程も楽しめるサイトにしたいです）

 
また、画像のAI生成の防止と、サイト上から画像をダウンロードできない仕組みを導入したいなと思っています。
→画像のAI生成の防止については、noai・noimageaiを使って学習拒否ができる旨を少し調べていますので、そちらを試したいと思っています。
サイト上から画像ダウンロードできない仕組みとして、右クリックの禁止を導入したいと思います（JSで出来ない仕組みがあると調べましたので、試してみたいと思っています）

■ 機能候補
・ログイン機能
・ユーザーページ（各種SNSリンクを添付、埋め込めるようにしたい）
・フォロー機能
・画像投稿・保存機能（キャラ紹介ページ）
・キャラ紹介ページの文章内容編集・レイアウト編集機能
・フォームレイアウト（5パターンくらい用意しておいて、選択式で選べるようにする、色は部分ごとに選択できるようにしたい）
・いいね機能（コメントは設けない）
・各ユーザー毎のお問い合わせフォームの設定
・通知機能（いいね、フォロー新着、お問い合わせフォーム新着、お知らせ新着等）


■ 機能の実装方針予定
・APIのイメージは正直ついていません。
・ウェブサイトの土台がすでに用意されていて、ユーザーがある程度カスタマイズできるように実装したいので、まずは今までのカリキュラムを辿り、掲示板サイトを作成してから、細かい部分を変えて作成していこうと思っています。
