# Java OOP 复习资料

华东师范大学 2026 春季学期《面向对象编程 (Java)》期末复习资料，基于课程讲义 (Lecture 1-13) 与复习课 (Course Review) 整理而成。

## 文件说明

| 文件 | 说明 |
|------|------|
| `java-oop-review.html` | 主复习文档，浏览器直接打开即可阅读 |
| `_shared/fonts/` | 文档内嵌字体文件 (JetBrains Mono + Instrument Sans) |

> 直接在浏览器中打开 `java-oop-review.html` 即可使用，无需联网。

## 内容结构

| 章节 | 主题 | 核心考点 |
|------|------|----------|
| 00 | 考试信息 | 时间、形式、题型分值 |
| 01 | 面向对象编程概述 | 对象三要素、组合 vs 继承 |
| 02 | Java 类型 | 基本类型、引用、不可变类型、final |
| 03 | Java 控制结构 | == vs equals()、字符串连接、传值机制 |
| 04 | 类 | 静态成员、this/super、初始化顺序、重载 vs 重写 |
| 05 | Java 包 | package/import、包结构与目录结构 |
| 06 | 访问控制 | public/private/protected/package access |
| 07 | 类的复用 | 组合、继承、构造函数调用链、Object 类 |
| 08 | Upcasting 与多态 | 动态绑定规则、Downcasting |
| 09 | 接口与抽象类 | abstract、interface、多接口实现、接口扩展 |
| 10 | 内部类 | 内部类、匿名类、Outer.this 引用 |
| 11 | 容器 | List/Set/Queue/Map、ArrayList/LinkedList/HashMap 原理 |
| 12 | 异常 | throw/try-catch-finally、throws、异常继承体系 |
| 13 | I/O | InputStream/OutputStream、装饰器、异常处理 |
| 14 | 泛型 | 泛型类、泛型接口、类型安全 |
| 15 | 编程题预设算法 | BFS、DFS、枚举、回溯 |
| 16 | 考试不包含的内容 | char unicode、左值右值、GC 实现原理、工厂模式等 |
| 17 | 课堂小测 | 11 道随堂小测题及答案解析 |

## 考试重点

根据老师复习课强调：

- **容器**：HashMap、ArrayList、LinkedList 的底层实现原理必须掌握
- **异常**：try-catch-finally 机制、throws 声明
- **I/O**：InputStream/OutputStream、正确处理 I/O 异常（必考）
- **算法**：默认掌握 BFS、DFS、枚举、回溯
- **指针/引用**：一定会考

## 考试信息

- **时间**：6 月 25 日 上午 8:00 - 10:00
- **地点**：文史楼 107
- **形式**：闭卷，无补考
- **题型**：选择 + 问答 60%，编程 40%（需写完整程序）

## 数据来源

- 课程讲义：[ecnu-oop-java/ecnu-oop-java-up/26-Spring](https://github.com/ecnu-oop-java/ecnu-oop-java-up/tree/main/26-Spring)
- 参考教材：*Thinking in Java (4th Edition)*, Bruce Eckel
