# LTやるなら！Rabbit！

author
: 山下智矢

institution
: 株式会社Inner Resource

# 何をするか

{:.center}
{::tag name="large"}Rubyist におすすめの{:/tag}
{::tag name="large"}スライド作成ツールの紹介{:/tag}

# エンジニアとスライド

{:.center}
LTのスライドどうやって作ってる？

# エンジニアとスライド

- テキストベースが好き
- CLIが好き
- プログラミングが好き
- {::wait/} Ruby が好き❤️

{::wait/}ならば [Rabbit](https://rabbit-shocker.org/ja/) を使いましょう🐰

# Rabbit の特徴

- Markdown, rd, Wiki記法 
- 20年以上の老舗 gem
- Matz はじめ多くの Rubyist が使ってる
- {::wait/}スライドを gem として公開する文化（）
- {::wait/}テーマを ruby で開発できる

# Rabbit の特徴

豊富なプレゼン機能

- うさぎとかめ
- 虫眼鏡（ctl + 右クリック）
- スポットライト（ダブル右クリック）
- 落書き機能
- マウスジェスチャ（右ドラッグ）
- {::tag name="x-small"}(ラビットホール、ホワイト/ブラックアウト、twitter連携){:/tag}

# スタイル

{::tag name="x-large"}大きなテキスト{:/tag}

{:.center}
中央寄せテキスト

{:.right}
右寄せテキスト

```
{::tag name="x-large"}大きなテキスト{:/tag}
{:.center}
中央寄せテキスト
{:.right}
右寄せテキスト
```

# スタイル

![](https://raw.githubusercontent.com/rabbit-shocker/rabbit/master/data/rabbit/image/cozmixng-images/cozmixchu.png "こずみっくちゅー")

- 透かしや CopyRight、テーブルもできるよ

# うさぎとかめ

とりあえずこれだけでも使う価値あり
ダラダラと話さなくなる
進行度が一目で伝わる👍

```sh
rabbit --allotted-time 300 lt.md
```

# ちなみに

インストールがちょっと大変だったよ
使い方・記法などのドキュメントは未成熟

多分普通にスライド作るなら [Marp](https://marp.app/) がいいよ

# Marp

- CLI, VSCode拡張
- md
- html, pptx出力
- css でテーマ書ける
- ツールも充実
- プレゼン機能は特になさそう

# まとめ
- Ruby が好きなら Rabbit おすすめ！
- 普通に手軽にスライド作るなら Marp がおすすめ！

# リンク
- Rabbit公式: [Rabbit - はじめに](https://rabbit-shocker.org/ja/)
- Rabbrtスライド公開ページ: [Rabbit Slide Show](https://slide.rabbit-shocker.org/)
- Marp公式: [Marp: Markdown Presentation Ecosystem](https://marp.app/#get-started)