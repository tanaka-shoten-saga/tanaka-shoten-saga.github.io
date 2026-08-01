# 炭火焼肉 田中商店

佐賀駅から徒歩4分、炭火と和牛の焼肉店の公式サイトです。

**公開URL** — https://jumpei0530.github.io/tanaka-shoten/

| | |
|---|---|
| 住所 | 佐賀市駅南本町3-8 くさばビル2F（〒840-0816） |
| 営業 | 17:00–24:00（L.O. 23:00）／ 年中無休 |
| 席数 | 22席・全席禁煙 |
| 電話 | 050-8888-1239 |
| Instagram | [@tanakashouten_yakiniku](https://www.instagram.com/tanakashouten_yakiniku/) |

姉妹店: 芦田商店 佐賀駅前店（野菜巻き串の居酒屋）

## 構成

素のHTML/CSS/JavaScriptで、ビルド作業はありません。`index.html` を編集して push すれば、GitHub Pages が自動で反映します。

```
index.html          本体
assets/css          スタイル
assets/js           スクリプト
assets/images       写真
sitemap.xml         サイトマップ
robots.txt          クローラ向けの指定
```

## 検索とAIからの見え方

`index.html` に schema.org の構造化データを埋めています。`Restaurant` / `Menu` / `MenuSection` / `OpeningHoursSpecification` / `GeoCoordinates` / `PostalAddress`。

**住所・営業時間・電話・メニューを直したときは、必ず構造化データ側も直してください。** 表示だけ直すと、検索結果やAIの回答が古いままになります。ここがズレるのがいちばん厄介です。

## URL について

`canonical` `og:url` `og:image` と構造化データの `url` に、公開URLを直書きしています。**独自ドメインに移すときは、この4か所と `sitemap.xml` `robots.txt` を一緒に書き換えてください。**

## ライセンス

デザインのベースは [Grilli](https://github.com/codewithsadee/grilli)（codewithsadee 作・MITライセンス）です。原文の著作権表示は `LICENSE` に残しています。

写真・文章・店舗情報は田中商店に帰属します。
