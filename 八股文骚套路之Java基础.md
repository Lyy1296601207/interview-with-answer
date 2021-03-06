## Java 基础面试准备

**Java 基础常见面试题汇总** ：

1. Java 语言的特点（如果你简历上有提到 C++ 可能还会问你 Java 和 C++ 的区别）。【⭐⭐】
2. 比较 JVM 和 JDK 以及 JRE 。【⭐⭐⭐】非常非常基础的一个问题！学了 Java 之后还不知这个问题如何回答的小伙伴自觉去面壁吧！
3. 为什么说 Java 语言“解释与编译并存”。【⭐⭐】
4. Java 基本类型有哪几种，各占多少位？【⭐⭐】前些年面试常问的一个问题，去年面试过程中只京东问我了
5. Java 泛型，类型擦除。【⭐⭐⭐】
6. `==` 和 `equals()` 的区别。【⭐⭐⭐】：这个问题在 2018 年之前几乎是面试必问的问题，但是现在大厂以及比较少问了，现在小厂中厂问的多。
7. **`hashCode()` 和 `equals()`** 【⭐⭐⭐⭐】：这个问题经常问，面试官经常问为什么重写 `equals()` 时要重写 `hashCode()` 方法？另外，这个问题经常结合着 `HashSet` 问。
8. **重载和重写的区别。** 【⭐⭐⭐⭐】
9. 深拷贝和浅拷贝。【⭐】
10. 面向对象和面向过程的区别。【⭐⭐⭐】
11. 成员变量与局部变量的区别。【⭐⭐⭐】
12. 面向对象三大特性是什么。并解释这三大特性。【⭐⭐⭐⭐】
13. **`String`、`StringBuffer` 和 `StringBuilder` 的区别。** 【⭐⭐⭐⭐】
14. Java 异常。【⭐⭐⭐】：不会问的特别细。经常的问法是异常可以分为哪几种，然后你答了可检查异常和不可检查异常以后，会让你举例可检查异常有哪些，不可检查有哪些。然后，异常的代码要会写，有一场字节的面试，直接让我写一个把异常捕获了然后抛出去的代码。
15. 序列化和反序列化【⭐⭐】
16. 反射【⭐⭐】面试官可能会问你什么是反射，它的优缺点是什么，有哪些应用场景。
17. `List`、Set`、` `Map` 的区别。【⭐⭐】
18. **`ArrayList` 和 `LinkedList` 的区别。**【⭐⭐⭐⭐】：答清楚每个分别采用什么数据结构，对比相应的优点和缺点。
19. 比较 `HashSet`、`LinkedHashSet` 和 `TreeSet` 三者的异同。【⭐⭐⭐】
20. HashMap 多线程操作导致死循环问题。【⭐⭐⭐】jdk 1.8 后解决了这个问题，但是还是不建议在多线程下使用 `HashMap`,因为多线程下使用 `HashMap` 还是会存在其他问题比如数据丢失。并发环境下推荐使用 `ConcurrentHashMap` 。
21. HashMap 的长度为什么是 2 的幂次方。【⭐⭐⭐】主要是考虑到了对运算效率的提升。
22. **`HashMap`、`HashTable`、以及 `ConcurrentHashMap` 的区别。**【⭐⭐⭐⭐⭐】：现在面试的超高频考点。当面试官问到这个问题的时候，展现你背面试八股文能力的机会来了。你可以展开去讲在 Java7 和 Java8 中 `HashMap` 分别采用什么数据结构，为什么 Java8 把之前的`头插法`改成了`尾插法`，怎样实现`扩容`，为什么`负载因子`是 `0.75`，为什么要用`红黑树`等等一系列的东西。只要面试官不打断我，我在这个知识点上能背到面试官下班。