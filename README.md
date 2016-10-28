Type-Aligned
============

Type-aligned data-types in Scala.

Can be used to implement, for example, stack-safe function composition.

Contains:
 - [`APair`](https://github.com/TomasMikula/type-aligned/blob/master/src/main/scala/typealigned/APair.scala), type-aligned pair.
 - [`AList`](https://github.com/TomasMikula/type-aligned/blob/master/src/main/scala/typealigned/AList.scala), type-aligned list.
 - [`AList1`](https://github.com/TomasMikula/type-aligned/blob/master/src/main/scala/typealigned/AList1.scala), type-aligned non-empty list.
 - [`FreeCompose`](https://github.com/TomasMikula/type-aligned/blob/master/src/main/scala/typealigned/FreeCompose.scala), type-aligned sequence with _O(1)_ addition to both ends and _O(1)_ concatenation.
 - [`Binary`](https://github.com/TomasMikula/type-aligned/blob/master/src/main/scala/typealigned/Binary.scala), binary counter-like builder of composed objects in a balanced fashion. Used in other sequences to implement balanced reduction.
