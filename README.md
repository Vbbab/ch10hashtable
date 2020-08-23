# Ch. 10: Hashtable (`Set`, `HashSet`, `Map`, `HashMap`)

## Set
A collection that **cannot** contain duplicate elements.

Type: `Interface` (Non-implemented)

* Key methods:
    
    `add(E e)`: Add an element to the set
    
    `equals(E e)`: compares this set with the other for equality
    
    `size()`: returns the number of elements in this set (its cardinality)
    
    `contains(E e)`: Element exists? (bool)

Related: `TreeSet` (Gold), `LinkedHashSet` (Gold)

# HashSet

Is a class, implements methods from interface `Set`

* Key: `iterator()`, returns an iterable iterator over the elements in the set

* `<K>` key type

```java
HashSet<Integer> testSet = new HashSet<Integer>();
```
Creates a `HashSet`, named `testSet`, which excepts an `Integer` key and a `String` value


# Map
Type: `Interface` (Non-implemented)
`<K, V>` key-value pair

```Map<String, String> myMap; // Key: String, Value: String```
- Key methods:
    
    `put(K key, V value)` - Puts a thing into the `Map`. **If `key` exists within the `Map`'s keys, its value is replaced with `value`.**
    
    
    
# HashMap

# General
| **:warning:Warning: `equals()` and `hashCode()` are both user/implementation-defined, so *not necessarily checking by value.*** |
|---|