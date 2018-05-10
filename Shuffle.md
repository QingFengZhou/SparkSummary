
# 什么是shuffle
Certain operations within Spark trigger an event known as the shuffle. The shuffle is Spark’s mechanism for re-distributing data so that it’s grouped differently across partitions. This typically involves copying data across executors and machines, making the shuffle a complex and costly operation.

官网解释：某些spark算子会产生shuffle。Shuffle是Spark的一种机制，数据在各个分区（partition）之间重新分布，分组（形成新的分区）。此过程涉及到在多个executor和多个machine之间copy数据，因此是一种负责的、代价很高的操作。
