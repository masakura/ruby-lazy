### これは NG

```ruby
# 戻ってきません...

p (1...Float::INFINITY).find_all {|i| i <= 10}.take(3)
```
