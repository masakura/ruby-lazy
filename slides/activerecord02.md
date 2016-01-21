### 使い方

30 代の人の名前の配列を作る

```ruby
names = Member.where(age: 30..39).pluck(:name)
```

発行される SQL はこんな感じらしい <!-- .element: class="fragment" data-fragment-index="1" -->

```sql
SELECT id FROM members WHERE age BETWEEN 30 AND 39
```
<!-- .element: class="fragment" data-fragment-index="1" -->
