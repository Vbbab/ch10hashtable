# Ch. 10: Hashtable (`Set`, `HashSet`, `Map`, `HashMap`)

## Set
A collection that **cannot** contain duplicate elements.

Type: `Interface` (Non-implemented)

* Key methods:
    
    `add(E e)`: Add an element to the set
    
    `equals(E e)`: compares this set with the other for equality
    
    `size()`: returns the number of elements in this set (its cardinality)
    

Related: `TreeSet` (Gold), `LinkedHashSet` (Gold)

# HashSet

Is a class, implements methods

* Key: `iterator()`, returns an iterable iterator over the elements in the set

* `<K, V>` key-value pair

```java
HashSet<Integer, String> testSet = new HashSet<Integer, String>();
```
Creates a `HashSet`, named `testSet`, which excepts an `Integer` key and a `String` value


# Map
# HashMap

# General
| **:warning:Warning: `equals()` and `hashCode()` are both user/implementation-defined, so *not necessarily checking by value.*** |
|---|