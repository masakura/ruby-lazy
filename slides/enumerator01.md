### Enumerator

Ruby に昔からある遅延リスト

```ruby
# 0
# 1
# 2

Enumerator.new([0, 1, 2]).each do |i|
  p i
end
```

最近はこんな書くらしい

```ruby
[0, 1, 2]).to_enum.each do |i|
  p i
end
```

* 配列を Enumerator にラッピングするのは多分意味がない... <!-- .element: class="fragment" data-fragment-index="1" style="font-size: 80%" -->
