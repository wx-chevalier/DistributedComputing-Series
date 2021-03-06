# 批处理

互联网的发展产生了所谓的大数据（TB 或 PB），不可能在一个有限的时间范围内将数据拟合到一台机器上或用一个程序处理它。在批处理中，新到达的数据元素被收集到一个组中。整个组在未来的时间进行处理（作为批处理，因此称为“批处理”）。确切地说，何时处理每个组可以用多种方式来确定，它可以基于预定的时间间隔（例如，每五分钟，处理任何新的数据已被收集）或在某些触发的条件下（例如，处理只要它包含五个数据元素或一旦它拥有超过 1MB 的数据）。

![基于时间的批处理间歇过程](https://s2.ax1x.com/2019/10/03/uwHkQJ.png)

通过类比的方式，批处理就像你的朋友（你当然知道这样的人）从干衣机中取出一大堆衣物，并简单地把所有东西都扔进一个抽屉里，只有当它很难找到东西时才分类和组织它。这个人避免每次洗衣时都要进行分拣工作，但是他们需要花费大量时间在抽屉里搜索抽屉，并最终需要花费大量时间分离衣服，匹配袜子等。当它变得很难找到东西的时候。历史上，绝大多数数据处理技术都是为批处理而设计的。传统的数据仓库和 Hadoop 是专注于批处理的系统的两个常见示例。

术语 MicroBatch 经常用于描述批次小和/或以小间隔处理的情况。即使处理可能每隔几分钟发生一次，数据仍然一次处理一批。Spark Streaming 是设计用于支持微批处理的系统的一个例子。

# TBD

- http://dist-prog-book.com/chapter/8/big-data.html
