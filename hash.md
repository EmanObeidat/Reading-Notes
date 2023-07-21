### Hash Tables:
```
Similar to a library index where books are arranged by title is a hash table. Without having to look through every shelf, you may easily discover the shelf that holds a particular book by using the index. Similar to this, a hash table creates an index or hash value for each key using a hash function, enabling you to quickly obtain values without having to look through every entry.

A hash table, commonly referred to as a hash map, is a type of data structure used in computing to build an associative array or dictionary. It is a type of abstract data that associates values with keys. An array of buckets or slots are used in a hash table to provide an index, also known as a hash code, from which the requested data can be retrieved. The key is hashed during lookup, and the resulting hash shows where the relevant value is kept.
```

### related Terminology

1.Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
2.Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.
3.Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.


### Why we use hashtable?

Hash tables are widely used data structures in computer science and programming due to their efficiency and ability to provide fast access to data. They are also known as hash maps or associative arrays.

```
 Here are some of the key reasons why we use hash tables:
 1.Fast data retrieval
 2.Key-value storage
 3.Data organization
 4.Searching efficiency
```




### how we implement hashtable?
1. Choose a suitable data structure for the hash table
2. Define a hash function
3.Handle collisions
4.Insertion and retrieval operations
5.Resizing


## Hashing Technique

To achieve a good hashing mechanism, It is important to have a good hash function with the following basic requirements:

1. Easy to compute: It should be easy to compute and must not become an algorithm in itself.

2. Uniform distribution: It should provide a uniform distribution across the hash table and should not result in clustering.

3. Less collisions: Collisions occur when pairs of elements are mapped to the same hash value. These should be avoided.

## what are the methods in hashtable?
```
In a hashtable, there are typically several methods or operations that allow you to interact with the data structure. The specific methods may vary depending on the programming language and implementation, but here are some common methods you would find in a hashtable:

Insert(key, value): This method allows you to add a new key-value pair to the hashtable. The key is hashed to determine the index where the value should be stored. If there is a collision, the collision resolution strategy (chaining or open addressing) is used to handle it.

Get(key): This method retrieves the value associated with the given key. It calculates the hash of the key to find the index and then returns the corresponding value. If the key is not found in the hashtable, an appropriate response like null or an exception might be returned.

Remove(key): This method removes the key-value pair associated with the given key from the hashtable. It finds the index using the hash function and deletes the entry. Again, the collision resolution strategy is used if needed.

ContainsKey(key): This method checks whether the given key exists in the hashtable. It calculates the hash of the key and verifies if an entry exists at the corresponding index.

Size(): This method returns the number of key-value pairs currently stored in the hashtable.

IsEmpty(): This method checks if the hashtable is empty, i.e., it contains no elements. It returns true if there are no elements and false otherwise.

Clear(): This method removes all key-value pairs from the hashtable, effectively clearing it and making it empty.

Resize(newSize): As the number of elements in the hashtable increases, a resize operation might be needed to maintain a reasonable load factor. This method creates a new hashtable with a different size and rehashes all the existing key-value pairs into the new hashtable.

Keys() and Values(): These methods return collections or iterators containing all the keys and values stored in the hashtable, respectively.

LoadFactor(): The load factor is the ratio of the number of occupied slots
```