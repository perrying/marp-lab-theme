---
marp: true
paginate: true
theme: itlab
footer: example slides
---
<!-- 
_class: title
_paginate: false
_footer: <br>
 -->
# Marpを使った資料作成
## Teppei Suzuki
### Denso IT Laboratory, Inc. Japan
---
# テンプレートの使い方

- class
  - classはデフォルト（このページの形式）と**title**,**end**の3つからなる
    - titleは一番元のスライド、endはロゴのみ
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
