---
transition: fade-out
---

# リンターを使おう

* 変数はキャメルケース、クラス名はパスカルケースとか決めたところでレビューでいちいちチェックするのは煩わしい
* リンターを導入するといい感じになる


---
layout: cover
transition: fade-out
---


# 実際に頂いた声

* 「何か作るたび真っ赤になってて楽しい」
* 「普通に教えてもらうより勉強になります」
* 「もうない時代には戻れない」

---
layout: cover
transition: fade-out
---

# ではどういうJS/TSでどういうルールがいいのか

---
layout: cover
transition: fade-out
---

# airbnbに従おう

---
layout: center
transition: fade-out
---

# なぜか
## =>きちんと理由があるから（ないのもあるが）
例えば`すべての参照はconstを使用し、varを使用しない。`というルールの場合、その理由も併記されている。

> なぜ? 参照を再割り当でできないことで、バグに繋がりやすく理解しがたいコードになることを防ぎます。

https://mitsuruog.github.io/javascript-style-guide/#references--prefer-const

---
layout: center
transition: fade-out
---

# こんなものまである

for ofを使うと怒ります。
なぜなのかを考えてみましょう。

https://mitsuruog.github.io/javascript-style-guide/#iterators--nope
https://qiita.com/41semicolon/items/6ec0f6a9fdf7c97f1a41

