# algorithm
该项目用于算法学习。
## 1. 双向链表
双向链表也叫双链表，是链表的一种，它的每个数据结点中都有两个指针，分别指向直接后继和直接前驱。所以，从双向链表中的任意一个结点开始，都可以很方便地访问它的前驱结点和后继结点。本次需要实现的是双向链表。包括如下功能：
bool add(E e);添加元素至此列表的结尾。
bool add(int index, E e);添加元素至指定的index。
void addFirst(E e);将指定元素插入此列表的开头。
void addLast(E e);将指定元素插入此列表的结尾。
void clear();从此列表中移除所有元素。
bool contains(Object o);如果此列表包括指定。
E get(int index);返回此列表中指定位置处的元素。
int indexOf(Obiect o);返回此列表中首次出现的指定元素的索引，如果此列表中不包含该元素，则返回-1。
E remove(int index);从此列表中移除首次出现的指定元素（如果存在）。
E set(int index, E element);将此列表中指定位置的元素替换为指定的元素。
int size();返回此列表的元素数。
