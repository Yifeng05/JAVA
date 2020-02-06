# Contents
- [Java 基础](#java基础)
  - [包装类型和基本类](#integer-and-int)  
- [java容器](#java-collection)
  - [常见容器](#common-used)  
    -[Arraylist](#arraylist)
    -[Vector](#vector)
    -[LinkedList](#linkedList)
    -[HashMap](#hashmap)
    -[ConcurrentHashMap](#concurrentHashMap)
    -[LinkedHashMap](#linkedhashmap)
    -[WeakedHashMap](#weakedhashmap)


# java基础
我们这里就是一些知识啦
3. 索引列的顺序
让选择性最强的索引列放在前面。
索引的选择性是指：不重复的索引值和记录总数的比值。最大值为 1，此时每个记录都有唯一的索引与其对应。选择
性越高，查询效率也越高。
例如下面显示的结果中 customer_id 的选择性比 staff_id 更高，因此最好把 customer_id 列放在多列索引的前面。
