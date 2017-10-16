

# Collection

## List

* ArrayList : based on array, thread unsafe, only insert/delete item on the end, better efficiency

* LinkedList: based on Linked list, thread unsafe, can isert/delete any where

## Set

* HashSet : orderless

* LinkedHashSet : use Linked list to extend HashSet, ordered sequence

* TreeSet : based on tree, ordered sequence with on Comparator defined by user

## Queue: 

* LinkedList: implement inteface Deque, can add/delete item on both head/tail

* PriorityQueue : item with Priority, delete item with high Priority first



# Map

* HashMap : orderless map,

* LinkedMap : ordered map, 

* TreeMap

If we don't need to keep order, use HashMap, if we need order items by creation sequence or last visit order, use LinkedMap.
If we need to order items by key value, use TreeMap


# Others

* Vector: thread safe, function same as ArrayList

* Stack: thread safe, extend vector

* HashTable: thread safe,function same as HashMap, extend Dictionary, both key/value cannot be null







reference :

http://www.jianshu.com/p/63e76826e852
https://yikun.github.io/2015/04/01/Java-HashMap%E5%B7%A5%E4%BD%9C%E5%8E%9F%E7%90%86%E5%8F%8A%E5%AE%9E%E7%8E%B0/
