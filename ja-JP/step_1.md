
次を使って円や楕円を描きます。`ellipse(x, y, 幅, 高さ)`

`ellipse`が呼び出される前に設定されていた輪郭線と塗りつぶしの値を使って楕円が描かれます。

--- code ---
---
language: python
filename: main.py
---

  ellipse(160, 220, 200, 100) # x, y, 幅, 高さ

--- /code ---

楕円の中心は、最初の2つの数値で指定された(x, y)座標になります。

3番目の数字は楕円の幅で、4番目の数字は高さです。

![x 160、y 220を中心とし、幅200、高さ100の楕円を示す出力領域](images/example.png)

真円を描くには幅と高さを同じにします。

