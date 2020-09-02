# collection 体系
### 介绍

* AbstractCollection 集合类，使用了模板模式，将重复的模版代码抽象到上层，避免重复的编写

* 抽象接口体系：List、Map、Array、Set（TreeSet,SortedSet）
* compareable 接口实现，需要注意对象判断不要使用减法或者亦或运算，会有溢出的风险，按照约定写成返回（-1，1，0）
* hashcode 和 equals 必须要同时重写