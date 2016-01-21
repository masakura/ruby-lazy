### Enumerable

Ruby に昔からある遅延リスト評価関数群のモジュール

* Iterator も Range もこれをミックスインしている

```ruby
# [1]

p (0..2).find_all {|i| (i % 2) != 0}
```

* 0 は true 扱いなんよね... <!-- .element: class="fragment" data-fragment-index="1" style="font-size: 80%" -->
