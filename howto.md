## marp pluginをインストール

<img width="700" alt="スクリーンショット 2021-05-02 17 40 46" src="https://user-images.githubusercontent.com/33768/116807321-8cfb5a80-ab6d-11eb-9350-08d01751f663.png">

## User/Projectにテーマのパスを追加する

<img width="700" alt="スクリーンショット 2021-05-02 17 39 09" src="https://user-images.githubusercontent.com/33768/116807297-5e7d7f80-ab6d-11eb-8790-5aa83135652c.png">

`http://raw.githubusercontent.com/DensoITLab/marp-lab-theme/main/itlab.css`を追加する．現バージョンでは，httpsにするとcssを読み込んでくれない．

`.vscode/setting.json`に下記のように記述しても同じ．

```
{
    "markdown.marp.themes": [
        "http://raw.githubusercontent.com/DensoITLab/marp-lab-theme/main/itlab.css"
    ]
}
```

## プレゼンのファイルの設定

まず，markdownファイルの頭に下のフォーマットを記述する．

```
---
marp: true
paginate: true
theme: itlab
footer: example slides
---
```
もしくは
```
---
marp: true
paginate: true
theme: itlab
footer: example slides
---
```

CSSの設定が正しければ，上のヘッダをmarkdownに書けば，marpがテーマを設定してくれる．
