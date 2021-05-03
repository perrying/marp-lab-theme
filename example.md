---
marp: true
paginate: true
theme: itlab
footer: example slides
header: Confidential
---
<!-- 
_class: title
_paginate: false
_footer: <br>
 -->
# Marpを使った資料作成
## Taro Tanaka
### Denso IT Laboratory, Inc. Japan
---
# テンプレートの使い方

- class
  - classはデフォルト（このページの形式）と**title**,**end**の3種類
    - titleは一番目のスライド、endはロゴのみ
    - titleは\#でタイトル、\##で名前、\###でその他所属などを想定
    - 全て開始位置は絶対位置が決められているので、変更する場合はcssをいじるか、各スライドブロックの中身で下記のように指定
  ```
  <style scoped>
    h1 {
        top: 50%;
    }
  </style>
  ```
---
<!-- 
_class: title
_paginate: false
_footer: <br>
 -->
<style scoped>
h1 {
    top: 50%;
}
</style>

# top: 50%にした場合のタイトル位置

---
<!-- 
_class: end
_paginate: false
_footer: <br>
 -->
