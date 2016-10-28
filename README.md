Type-Aligned
============

Type-aligned data-types in Scala.

Can be used to implement, for example, stack-safe function composition.

Contains:
 - `APair`, type-aligned pair.
 - `AList`, type-aligned list.
 - `AList1`, type-aligned non-empty list.
 - `FreeCompose`, type-aligned sequence with _O(1)_ addition to both ends and _O(1)_ concatenation.
 - `Binary`, binary counter-like builder of composed objects in a balanced fashion. Used in other sequences to implement balanced reduction.
