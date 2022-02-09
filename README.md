# hello-algorithms
Learning algorithms and data structures.

## algorithms-java
### algorithms
**1.[布隆过滤器](https://github.com/lewiszlw/hello-algorithms/blob/main/algorithms-java/src/main/java/lewiszlw/algorithms/BloomFilter.java)**

bitmap使用java.util.BitSet，hash函数采用HashMap中的hash函数

**2.[经典排序算法](https://github.com/lewiszlw/hello-algorithms/tree/main/algorithms-java/src/main/java/lewiszlw/algorithms/sort)**

**3.[蓄水池采样算法](https://github.com/lewiszlw/hello-algorithms/blob/main/algorithms-java/src/main/java/lewiszlw/algorithms/ReservoirSampling.java)**

### data-structures
**1.[字典树 (前缀树)](https://github.com/lewiszlw/hello-algorithms/blob/main/algorithms-java/src/main/java/lewiszlw/datastructure/TrieTree.java)**

**2.[LRUCache](https://github.com/lewiszlw/hello-algorithms/tree/main/algorithms-java/src/main/java/lewiszlw/datastructure/lrucache)**

①[HashMap + 单链表实现](https://github.com/lewiszlw/hello-algorithms/blob/main/algorithms-java/src/main/java/lewiszlw/datastructure/lrucache/LRUCache1.java)

②[HashMap + 双向链表实现](https://github.com/lewiszlw/hello-algorithms/blob/main/algorithms-java/src/main/java/lewiszlw/datastructure/lrucache/LRUCache2.java)

### problems

**1.[两线程交替打印奇偶数](https://github.com/lewiszlw/hello-algorithms/blob/main/algorithms-java/src/main/java/lewiszlw/problems/TwoThreadPrintOddEvenNumber.java)**

每个线程while循环，保证线程不会立即执行完成，然后利用锁机制等保证两个线程切换，或者利用操作系统时间轮转特性来切换线程

**2.[生成者-消费者问题](https://github.com/lewiszlw/hello-algorithms/tree/main/algorithms-java/src/main/java/lewiszlw/problems/producerconsumer)**

待优化：生成者和消费者在同一队列，但是两者不会同时处于wait状态

**3.[参加表演最多场次](https://github.com/lewiszlw/hello-algorithms/blob/main/algorithms-java/src/main/java/lewiszlw/problems/MaxPlaysToAttend.java)**

简述：N场表演，时间表以[{startTime, endTime}...]给出，计算最多能参加几场

解决方法：贪心法

**4.[背包问题](https://github.com/lewiszlw/hello-algorithms/tree/main/algorithms-java/src/main/java/lewiszlw/problems/knapsack)**

01背包问题

**5.[栈排序](https://github.com/lewiszlw/hello-algorithms/blob/main/algorithms-java/src/main/java/lewiszlw/problems/SortStack.java)**

简述：将一个栈内的元素进行升序（栈顶最大）排序，要求额外空间只能使用栈
