# Hashtables

## Terminology

It is used to find the index of the array in the case of a hashtable. Buckets - A bucket is the content of each index of the hashtable's array. Each index corresponds to a bucket. Collisions - When more than one key is hashed to the same place in the hashtable, it's called a collision.

Let's assume we have a list of Seattle neighborhood names and the zip codes that correlate to them. Now we want to be able to look up a neighborhood and get its zip code by searching through the data. We could accomplish this with a for loop that loops over each piece of data until it finds the neighborhood name, then returns the zip code to that location. This would be an O read operation because it necessitates the usage of a computer.

The reason why searching for a piece of data in a collection is O isn’t because the array is slow, it’s just that we have to look through all N things in the collection. Instead of adding elements to an array from beginning to end, a hash map uses a «hash function» to place each item at a precise index location, based off it’s key.

## Hashing

A hash code, in essence, converts a key into an integer. Randomness should never be used in hash codes.
«Buckets» are contained in each index of the array. Each of these "buckets" has a single key/value pair. When a bucket has no entries, the buckets all begin with a null value. When a key creates a hashCode that corresponds to an index, the hash table overwrites the value of each bucket.

## Collisions

When more than one key hashes to the same index in an array, a collision occurs. A «perfect hash», as previously stated, will never have any collisions. This is referred to as a collision. Collisions are avoided by altering the buckets' initial state.


Because each index in the array may contain many key/value pairs, it is referred to as a "bucket." Because various keys might link to the same bucket, it's critical to keep the full key/value combination, not just the value, in the bucket.. If only values were stored in buckets then it would be impossible to determine which value to return when a key led you to a bucket. This is similar to the original neighborhood names stored in an array with their zip codes shown earlier.
Here’s an actual example of just one bucket in a real hash map. In this example the two different keys «Pioneer Square» and «Alki Beach» happen to ultimately resolve to the same bucket. When we look at the bucket we see a representation of the Linked List that exists there. Pioneer Square was added first, so it’s at the front of the list.

Then there's Alki Beach, which is the second link in the chain.
Although the sum hashes for «Pioneer Square» and «Alki Beach» differ, they eventually resolve to the same bucket index. Their modulo bucket hashes
Any number of buckets can be used in a hash map. A hash map with only a few buckets will be highly packed and have a lot of collisions. A hash map with more buckets will be poorly populated, resulting in fewer collisions but potentially a lot of vacant space. A hash table may begin with only a few buckets, compute its own load factor, identify when it becomes overburdened, and grow and add additional buckets to itself to handle more data.

The first hash table only has 7 buckets. The second has 100 buckets. Notice that even though the second hash table has 100 buckets there are still some collisions.

Once you determine the index of where it should be placed, go to that index

If something does exist, add the new key/value pair to the data structure within that bucket.

## Basics of Hash Tables

Hashing is a technique that is used to uniquely identify a specific object from a group of similar objects. Some examples of how hashing is used in our lives include:
- Each student at a university is given a unique roll number, which may be used to access information about them.
- Each book in a library is given a unique number that may be used to find out information about it, such as its specific location in the library or the users to whom it has been distributed.

Assume you have an item to which you'd want to assign a key to make searching easier. You may use a basic array like a data structure to store the key/value pair, where keys can be used directly as an index to store values. A key is assigned to each element. You can access the element in O time by using that key.
### Hash function

A hash function is any function that can be used to map a data set of an arbitrary size to a data set of a fixed size, which falls into the hash table.
