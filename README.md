# Ruby初級者向けレッスン 69回
## ブロック
[発表資料](https://github.com/higaki/learn_ruby_kansai_84/blob/master/print.pdf)

### 演習問題1
0 から 9 までの数値をもつ配列 a がある。

    a = (0..9).to_a
    a   # => [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

* 各要素を順番に表示しよう。
* 各要素を文字列にした配列を作ろう。
* 各要素を 2倍した値を持つ配列を作ろう。
* 全要素の合計値を計算しよう。

### 演習問題2
0 から 9 までの数値をもつ配列 a がある。

    a = [*0..9]
    a   # => [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

* 奇数の要素だけを持つ配列を作ろう。
* ただし `odd?` メソッドは使用禁止。

### 演習問題3
`Enumerable#map` を自作してみよう。

    module Enumerable
      def my_map
        ......
      end
    end

ただし `Enumerable#map` と `Enumerable#map!` は使用禁止。
