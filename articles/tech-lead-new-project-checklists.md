# Tech Lead 的新项目检查清单


这些是关于 Tech Lead 需要做什么，以及何时到达新项目的会议的笔记。智慧来自于 Thoughtworks 的 @JimBarritt  - 我只是个搬运工。

请注意，此列表既适用于 Tech Lead 来到已有的项目，也适用于整个团队/产品是新项目的项目。

前两个显然是 “两个最可能的死亡或受伤原因”：

1). 基础设施

 - 生产环境在哪里？这是最重要的一个！它是什么样子的？什么时候准备好了？（开发环境是产品后的事后补充）
 - 我们怎么样才能上线？ 计划是什么？
 - 负载均衡
 - 防火墙
 - 证书

2). 第三方

 - 集成
 - 如果您无法控制的环境是混乱的，那么确保您自己的环境超级有序，规范、流畅、自动化，具有良好的范围规划等等更为重要。

3). 找到有权势的人

- 找到所有可以拒绝的人，持有钱包的人/可以签署预算，以及可以说 “是的，你做得很好” 并且了解他们的人。例如：
   - 架构师
 - 掌控数据保护的人（当心 “组织性疤痕组织（organisational scar tissue，即过度反应）”）
 - 在公共部门，SIRO（高级信息风险官）

4). 查找团队工作的所有顶级文档，阅读并理解

5). 预算和价值主张是什么？

 - 它的定义有多好？ 你为什么要做这项工作？ 愿景是什么？ 人们明白吗？
 - 一旦你找到这个信息，就要真的重复一遍
 - 如果有一些假设对整个成功至关重要，请在每个 showcase 开始时不断重复

6). 尝试与团队中的每个人一对一沟通

 - 尝试了解他们的目标是什么，特别是在项目上 - 并且对自己的目标保持透明。例如，如果您想要远离某些区域，请找到热衷于移动到这些区域的人
 - 他们的主要痛点和阻滞点是什么？

7). 与项目经理交朋友，了解他们如何管理预算。

 - 这有助于建立信任关系
 - 阅读 Chris Matts 的 [Real Options](https://theitriskmanager.wordpress.com/the-real-option-resource/)（实物期权）
 - 阅读 Bjarte Bogsnes 的 [超出预算](https://bbrt.org/bjarte-bogsnes/?gclid=CJvs4LiAyNUCFUK7GwodNNgFDQ)
 - 布雷特·安斯利在 [2016 年的敏捷大会上](https://www.youtube.com/watch?v=M72kFSilPCE)，做了一次关于金钱和团队以及如何进行核算的伟大演讲。
 - 阅读 Gregor Hohpe 的 [一个架构师对 IT 转型需要了解的 37 件事](https://leanpub.com/37things)
 - 不要试图成为金融领域神秘细节的专家，但要了解基本要素：资金是如何流动的，不同类型的工作是什么，运营支出和资本支出之间的区别是什么？

8). 如果有多个团队，找到并了解其他/她 Tech Lead

9). 了解交付三位一体的重要性：交付经理、产品负责人、技术主管

 - 这三个领域之间往往存在紧张关系
 - 与这些人建立关系
 - 所有三个都应该出现在所有决策中，否则它可能会出现偏差
 - Tech Lead 有时会在这些关系中略微侧重


10). Backlog：确保范围结构清晰

 - 使用故事树和 backlog 层次结构
 - 人们可以在更高水平的分组/规模上抗争
 - 你得到直升机上，俯视你正在建造的东西

11). 代码：

 - 确保您可以访问它
 - 保持与它的连接
 - 让几个开发者为您提供导游
    - 如果让更新的团队成员做这一个，可能会特别有启发性
 - 您需要能够可视化整个代码库（整体架构）
 - 第一次从头开始运行它有多难？

12). 疼点和阻塞者有哪些？

 - 项目经理是谈论这个问题的最好人选

13). 跨功能需求

 - 弹性和可扩展性
   - 是否会因负载而坍塌
 - 安全
   - 有人会闯入吗？
 - 自动化
   - 尽管自动化很棒，但不要因为认为：必须在一开始就设置好所有内容，因此而陷入困境。
   - 不一定优先考虑自动化 - 但要确定实际交付内容的优先级
   - 一旦你有了一些东西，并运行和迭代，这一切都很好 - 但你怎么打破那张初始的空白纸？
   - 你想要 pipeline 等，但作为一个原则，也许在项目开始时就有不同的物理定律
   - 不要花费六个星期，来构建一个没有实际可交付成果的 pipeline - 确保你有一些迭代的东西
   - 想象一下你正在构建的这个产品......想象一下你没有使用任何软件。然后把电脑带进去，问为什么 - 它会给你带来什么？哪里可以给你最大的价值？不要添加你不需要的东西
   - 想象一下，从业务角度来说，这是一个行走的骨架 - 例如，通过物理的方式来发布威士忌（delivering whisky）。您的部署步行骨架可以在顶部 - 只在您需要时自动执行某些操作
   - 这虽然是一种微妙的艺术 - 你不想最终得到大量的技术债
   - 您可以花费大量时间，来制定概念而无需使用该功能。
   - 可以同时使用技术 alpha  - 查看跨功能需求等
   - 尝试架构的行走骨架 - “可伸缩模型”

14). 作为 Tech Lead ，这个项目最让你害怕的是什么？

 - 做一个x轴上的时间图和不确定性的云。如果云真的很近，并且有大量的闪电......请注意它！
 - 这部分是关于风险管理

