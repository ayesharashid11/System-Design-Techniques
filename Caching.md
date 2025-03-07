# What Is Caching?
It is the process of storing and accessing data from memory(i.e. cache memory). The main feature of caching is to reduce the time to access specific data. 
Caching aims at storing data that can be helpful in the future. The reason for caching is that accessing the data from persistent memory(hard drives like HDD, 
SDD) used to take considerable time, thus, slowing the process. Hence, caching reduces the time to acquire the data from memory. Cache memory is used
to store the data which is a high-speed data storage layer and works for the purpose to reduce the need to access the data storage layer. Cache memory is
implemented by fast access hardware (RAM).

# Why caching is important?
Plays a vital role in improving system performance.
Reduces the overall time and makes the system time efficient.
Caching is unavoidable as it provides high performance in computer technology.
It often does not make any new requests.
It avoids reprocessing of the data.

# How caching mechanism works?
A partition is reserved in RAM for cache memory. Whenever a software requests data from storage, cache memory checks if the required data is already present in it. if it does exist in the cache the application, will read this data from the cache. 
If the required data does not exist in the cache memory, then, the application(software)will request the source(Hard Drives). After reading the data, the same data is stored in cache memory for future references.

As the cache memory is of limited size, the already existing data in the cache is to be removed for storing the new data. Caching system then requires an algorithm for removing the useless data. The algorithm will be designed to remove the data which is not going to get looked forward to soon.

# Types
Database Caching: 
A certain level of caching is already present in the Database. This internal cache is utilized for avoiding repeated queries. The last executed query result can be provided by the database immediately. The most commonly used database caching algorithm is based on storing key-value pairs in the hash table.
Memory-caching:
RAM is directly used for storing the cached data, this approach is faster than common database storage systems (Hard drives). This method is based on a set of key-value pairs in the database. The value is the cached data and the key is the unique value. Each set is uniquely identified. This Approach is Fast, efficient, and easy to implement.

# When to use
Static Content
-Read Intensive case
-Appliation Server cache
-CDN cache

# Cahce Eviction
A process of deleting  cached Data

1. Least Recently Used(LRU)
When the cache hits its capacity limit, the Least Recently Used (LRU) cache eviction policy is designed to eliminate the item that has been accessed the least recently. Items that have not been accessed for a longer period of time are assumed to be less likely to be used in the near future.
2. Least Frequently Used(LFU)
The least frequently accessed entries are eliminated first under the LFU cache eviction policy. It is based on the idea that things that are used the least are less likely to be needed later.
3. First-In-First-Out(FIFO)
First-In-First-Out (FIFO) is a cache eviction policy that removes the oldest item from the cache when it becomes full. In this strategy, data is stored in the cache in the order it arrives, and the item that has been present in the cache for the longest time is the first to be evicted
4. Random Replacement
Random Replacement is a cache eviction policy where, when the cache is full and a new item needs to be stored, a randomly chosen existing item is evicted to make room. 
