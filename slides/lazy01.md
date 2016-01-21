### Enumerator::Lazy

* Ruby 2.0 で導入
* `Enumerator` を継承
* `map` とか `find_all` とか `take` とかの戻り値が配列ではなく、`Enumerator::Lazy` を返します
* `Enumerable#lazy` を呼び出すことで、取得できます
