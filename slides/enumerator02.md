### Range

Ruby に昔からある範囲の遅延リスト

```ruby
# 0
# 1
# 2

Range.new(0, 2).each do |i|
  p i
end
```

こっちの方が短いし分かりやすいね!

```ruby
(0..2).each do |i|
  p i
end
```
