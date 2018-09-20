Bitcoin是在2008年由中本聪发明的，他出版了一篇题为“Bitcoin:A Peer-to-Peer Electronic Cash System”的文章。 他结合了诸如 b-money 和 HashCash 等先前的发明，创建了一个完全去中心化的电子现金系统，它不依赖中央机构进行货币发行或结算和验证交易。关键的创新是使用分布式计算系统 (称为“工作量证明”算法)每10分钟进行一次全球性的“选举”，从而允许分布式网络达成关于交易状态的共识。它优雅地解决了双重支出的问题，就是一个货币单位可以花费两次。以前，双重支出问题是数字货币的弱点，并通过中心化的票据交换所清算所有交易来解决。

比特币网络始于2009年，基于中本聪发布的参考实施指南，之后由许多其他程序员进行修订。为比特币提供安全 性和弹性的工作量证明算法(挖掘)的实施以指数级增长，现在超过了世界顶级超级计算机的组合处理能力。中本聪于2011年4月退出公众视线，将代码和网络的责任放在一个蓬勃发展的志愿者小组身上。中本聪和任何人都没有对比特币系统进行个人控制，这个系统基于完全透明的数学原理，开放源代码和参与者之间的共识持续运行。

作为一个程序员，你是不是对这一切感到好奇呢，从本章开始，我会通过解读源代码来带领你一起领略这一系统的魅力。下面简要介绍本系列教程的大纲：

1.  系统启动

    本部分主要讲述比特币系统的启动过程。包括命令参数的解析、RPC 命令的注册、钱包的验证、网络初始化、区块链数据的加载与对等节点的启动等。

2.  网络处理

    本部分讲述比特币底层 P2P 网络建立的过程。包括：套接字的处理、DNS种子节点的查找、如何连接到别的对等节点、消息处理的框架等。

3.  消息处理

    本部分讲述比特币协义的处理，任何想要与比特币通信的应用都要满足这些协义。包括了：对等节点的握手、保持节点连接的处理、获取地址的处理、设置费率与紧凑格式的请求、获取区块的处理等。

4.  交易处理

    本部分讲述的地址、钱包、交易、挖矿和脚本等相关内容。

5.  基于比特币构建应用程序

    本部分会仔细系统提供的 RPC 接口，以及对这些接口进行梳理，探讨可以构建一些应用。

