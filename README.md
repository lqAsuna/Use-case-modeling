# Use-case-modeling
## 用例建模
### a.Asg_RH用例图：

![image](https://github.com/lqAsuna/Use-case-modeling/blob/master/image/result1.png)

### b.携程用例图：

![image](https://github.com/lqAsuna/Use-case-modeling/blob/master/image/result2.png)

### c. 对比两个时代、不同地区产品的用例图，总结在项目早期，发现创新的思路与方法

过去与现在的基础功能基本相同，但过去由于硬件限制，订购软件的附加功能很少，而当前的软件添加了大量的附带功能，优点是功能更全面，但也带来了不易操作、界面繁琐的缺点

我们应当将消费者的需求摆在第一位，同时要注重软件的易操作性和轻量级，注重消费者反馈，即时更新软件功能，保证其随时适应市场

### d.Backlog图：

![image](https://github.com/lqAsuna/Use-case-modeling/blob/master/image/result3.png)

## 业务建模

### a.在（任务b）基础上，用活动图建模找酒店用例。简述利用流程图发现子用例的方法。

![image](https://github.com/lqAsuna/Use-case-modeling/blob/master/image/result4.png)

![image](https://github.com/lqAsuna/Use-case-modeling/blob/master/image/result5.png)

全部：

![image](https://github.com/lqAsuna/Use-case-modeling/blob/master/image/result6.png)

#### 以下情况可以帮助我们发现子用例：
- 流程图中能进一步抽象起来的某几个步骤可以作为一个子用例
- 某些步骤是一个循环的情况
- 某一步骤很明显是一个独立的子用例的情况

### b.选择你身边的银行 ATM，用活动图描绘取款业务流程

![image](https://github.com/lqAsuna/Use-case-modeling/blob/master/image/result7.png)
 
### c.查找淘宝退货业务官方文档，使用多泳道图，表达客户、淘宝网、淘宝商家服务系统、商家等用户和系统协同完成退货业务的过程。分析客户要完成退货业务，在淘宝网上需要实现哪些系统用例。

![image](https://github.com/lqAsuna/Use-case-modeling/blob/master/image/result8.png)
 
淘宝网需要实现生成退款订单、修改订单信息、提供卖家信息、同意\拒绝退货处理的用例

## 用例文本编写
- 摘要：简洁的一段式概要，通常用于主成功场景，在早期需求分析中为快速了解主题和范围而使用。 

    - 优点：内容简洁明了，可以快速了解系统包含的功能以及各功能之间的关系，同时编写所需的时间较短。
    - 缺点：内容不够详细，很多设计上的细节不能很好地体现出来。

- 非正式：用几个段落覆盖不同场景，一般在早期需求分析中使用。

    - 优点：几段式，相比摘要覆盖多了几个不同场景，简洁，快速了解流程。
    - 缺点：仍然不够正式，需要更加详细；仍不够全面，只能做快速了解主题和范围之用。

- 详述：详细编写所有步骤及各种变化，同时具有补充部分，在需求细化过程中使用。 

    - 优点：非常详细，详细编写所有步骤和各种变化，有严格的书写格式规范；细编写所有步骤和各种变化，包括前后置条件，能够直接作为编码的逻辑参考
    - 缺点：需要耗费巨量时间，只能对于具有重要架构意义和高价值用例详细编写，难以考虑周全，耗时较多，且内容较为冗长、繁琐。
