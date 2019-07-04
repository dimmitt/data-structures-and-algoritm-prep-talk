## data-structures-and-algoritm-prep-talk

#### python syntax 
operators:
<br/>https://www.tutorialspoint.com/python/python_basic_operators.htm
```
if statements: 
  if, elif, else;
functions: 
  def, return;
```

#### python b+ tree
https://github.com/NicolasLM/bplustree
https://gist.github.com/teepark/572734


random blog post about trees in python:
https://medium.com/the-renaissance-developer/learning-tree-data-structure-27c6bb363051

#### bisect python function: 
checks the array for the value and returns an index.
<br/>expects the list to be sorted, will match the first positive and return the index-1 if less and index+1 if more.
<br/>essentially: 
```python
num = 5
list=[1,2,3] #list2=[1,2,5,6]

def get_bisect:
  for i in list: 
    if (num < list[i] ):
      return i
    elif num == list[i]:
      return i+1
    elif(num > list[i] and i === list.length -1):
      return i+1
    else:
      return "should never be reached"
    
# expected value: 3
```

## b+ tree


## hashmap java example
```
/* switch 
import java.util.*;
*/
/* into
import java.util.HashMap;
import java.util.Set;
import java.util.Iterator;
import java.util.Map;
*/
```
https://www.tutorialspoint.com/java/java_hashmap_class.htm

## Java Stuff and C# give me a set of all inherited classes using reflection.

C# reflection: https://my.safaribooksonline.com/0596003390/csharpckbk-CHP-12-SECT-8

Java relection: https://stackoverflow.com/a/9240969/5283424

https://github.com/ronmamo/reflections
<br/>https://github.com/classgraph/classgraph

## from java.utils
https://www.tutorialspoint.com/java/java_collections.htm
</br>https://www.tutorialspoint.com/java/java_collection_interface.htm
</br>[linked-list](https://www.tutorialspoint.com/java/java_linkedlist_class.htm) [array_list](https://www.tutorialspoint.com/java/java_arraylist_class.htm) 

sets
</br>[hash_set](https://www.tutorialspoint.com/java/java_hashset_class.htm): Extends AbstractSet for use with a hash table.
</br>[linked_hash_set](https://www.tutorialspoint.com/java/java_linkedhashset_class.htm): Extends HashSet to allow insertion-order iterations.
</br>[TreeSet](https://www.tutorialspoint.com/java/java_treeset_class.htm): Implements a set stored in a tree. Extends AbstractSet.

maps
[HashMap](https://www.tutorialspoint.com/java/java_hashmap_class.htm): Implements most of the Map interface and extending AbstractMap to use a hash table. 
</br>[TreeMap](https://www.tutorialspoint.com/java/java_treemap_class.htm): Extends AbstractMap to use a tree.
</br>[WeakHashMap](https://www.tutorialspoint.com/java/java_weakhashmap_class.htm): Extends AbstractMap to use a hash table with weak keys.
</br>[LinkedHashMap](https://www.tutorialspoint.com/java/java_linkedhashmap_class.htm): Extends HashMap to allow insertion-order iterations.
</br>[IdentityHashMap](https://www.tutorialspoint.com/java/java_identityhashmap_class.htm): Extends AbstractMap and uses reference equality when comparing documents.

[vector](https://www.tutorialspoint.com/java/java_vector_class.htm): synchrounous thread safe and slower than an array list.

[algorithms_from_java.util](https://www.tutorialspoint.com/java/java_collection_algorithms.htm): see the coding example.

## Ruby
graphs: https://github.com/monora/rgl
<br/>linear algerbra multi dimensional array: https://github.com/rbotafogo/mdarray

```
https://github.com/kanwei/algorithms
* Heaps              Containers::Heap, Containers::MaxHeap, Containers::MinHeap
* Priority Queue     Containers::PriorityQueue
* Deque              Containers::Deque, Containers::CDeque (C ext)
* Stack              Containers::Stack
* Queue              Containers::Queue
* Red-Black Trees    Containers::RBTreeMap, Containers::CRBTreeMap (C ext)
* Splay Trees        Containers::SplayTreeMap, Containers::CSplayTreeMap (C ext)
* Tries              Containers::Trie
* Suffix Array       Containers::SuffixArray

* Search algorithms
  - Binary Search            Algorithms::Search.binary_search
  - Knuth-Morris-Pratt       Algorithms::Search.kmp_search
* Sorting algorithms           
  - Bubble sort              Algorithms::Sort.bubble_sort
  - Comb sort                Algorithms::Sort.comb_sort
  - Selection sort           Algorithms::Sort.selection_sort
  - Heapsort                 Algorithms::Sort.heapsort
  - Insertion sort           Algorithms::Sort.insertion_sort
  - Shell sort               Algorithms::Sort.shell_sort
  - Quicksort                Algorithms::Sort.quicksort
  - Mergesort                Algorithms::Sort.mergesort
  - Dual-Pivot Quicksort     Algorithms::Sort.dualpivotquicksort
```

## Javascript
https://github.com/frptools/collectable - contains multiple structures including red-black-tree.
https://github.com/mauriciosantos/Buckets-JS
includes: Linked List Dictionary MultiDictionary Binary Search Tree Stack Queue Set Bag Binary Heap Priority Queue

## GoData Structures
https://github.com/emirpasic/gods

## C# algorithms + data structures
https://github.com/justcoding121/Advanced-Algorithms

## C bplus tree demo
https://github.com/begeekmyfriend/bplustree/tree/in-memory

## c++ 
veroni diagram: https://github.com/tomilov/sweepline
b+ tree: https://github.com/zcbenz/BPlusTree
