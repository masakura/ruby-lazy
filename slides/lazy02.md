### 使ってみる

```ruby
# 0
# 1
# 2

(1...Float::INFINITY).lazy.find_all {|i| i <= 10}.take(3).each do |i|
  p i
end
```

ちゃんと動きますね! <!-- .element: class="fragment" data-fragment-index="1" -->
