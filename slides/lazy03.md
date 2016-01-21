### lazy が必要な理由

* `Enumerable#map` の戻り値の型を配列から `Enumerator` に変更するのは?
  - 超破壊的な変更となり、今までのプログラムはほぼ 100% 動かなくなる <!-- .element: class="fragment" data-fragment-index="1" -->
* Enumerable#lazy_map とかは? <!-- .element: class="fragment" data-fragment-index="2" -->
  - メソッド名が増え過ぎる... <!-- .element: class="fragment" data-fragment-index="3" -->

ということだそうです <!-- .element: class="fragment" data-fragment-index="4" -->
