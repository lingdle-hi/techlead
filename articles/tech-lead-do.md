# Tech Lead 做些什么事？

原文链接：[What does a tech lead do?](https://www.bitlog.com/2017/10/12/what-does-a-tech-lead-do/)

这是在 Etsy 内部编写的。我被鼓励在我自己的个人博客上发帖，以便人们可以分享。 这些是我的意见，而不是 “Etsy 官方的”。

## 写这个的动机

在过去的 5 个月里，我一直是 Etsy 搜索体验团队的技术主管。我们的工程经理有一个很好的理念，即在经理和 Tech Lead 之间分配工作。工程经理负责将项目提升到工程师开始工作的程度。Tech Lead 确保一切都在此之后发生。因此，这旨在记录有助于推动 “之后的一切” 的思维方式。

拥有一个 Tech Lead 可以帮助我们的团队顺利开展工作。我们已经产生了相当大的总商品销售（Gross Merchandise Sales，GMS）。我们以可预测的时间表发布我们的项目，几乎没有戏剧性。我已经看到这个结构在过去成功了，无论是在 Etsy 还是以前的公司。

您可以学习如何成为 Tech Lead。你可以擅长它。有人应该这样做。它也可能是你。这个建议听起来有点奇怪，因为：

 - 这是许多公司的角色，但并不总是官方头衔
 - 不是每个团队都有
 - 工作很难，而且可能无法识别
 - 您不需要被视为 Tech Lead，就可以执行本文档建议的任何操作

但是当有一个人设定团队的技术方向时，团队会更有效地运行并更快地传播知识。

## Tech Lead 意味着谁？

一位正式或非正式领导 2-7 人项目的工程师。这不适用于大型团队，也不适合领导团队。根据我的经验，8-10 人是通信开销爆炸的拐点。此时，需要花费更多时间在流程和组织上。

## Tech Lead 的心态是什么？

这是一系列原则，可以为搜索体验带来良好的结果，或者是完成工作所必需的。 我正在记录我的经验中哪些方面有效。

## 更多责任→减少编写代码的时间

当我刚从大学毕业时，我在一个计算机视觉研究实验室工作。我认为最重要的是编写大量代码。这很好用。我的老板很高兴，我慢慢得到了更多的责任。但随后经济衰退袭击了军事分包商，该公司陷入了困境。生命快到你了！

所以我加入了 BigCo，再次开始在图腾柱的底部。我专注于编写大量代码，并学会在大型团队中进行编写。这很好用。我慢慢地获得了责任，最终被赋予了运行一个小项目的任务。在此之前，我一直专注于编写大量代码。所以我打算写很多代码，对吧？

错误。两周后，我的经理把我拉到一边说：“你的团队中没有人有任何事可做，因为你没有在三天内组织积压的任务。你为什么整个上午编码？在做其他任何事情之前，你需要确保你的团队顺利运行。“

好的，知道了。

所以我每天都会制作日历提醒，专注于为团队做额外的准备工作。当我做这项工作时，我们作为一个三人单位更快地移动。但我可以在我的代码统计数据中看到我开始更多地关注团队。有明显下降。即使我预料到这一点，我也感到内疚！提交和代码行是衡量生产力的非常简单的方法，但当您是 Tech Lead 时，您的首要任务是团队的整体生产力。而你只需要对抗内疚。你还会经历它。你只需要认识到这种感觉并通过它来完成。

## 先帮助别人

在你向前迈进之前说，你应该解锁你的团队听起来不错，但这在实践中意味着什么呢？

首先，如果你有工作，但有人需要你的帮助，那么你应该先帮助他们。作为一名高级工程师，你的时间是杠杆化 - 花费 30 分钟的时间可以节省别人的时间。这些数字听起来有些偏差，但这也是一个原则背后的原则，即错误会在发现它们之后变得更加昂贵。做事比做重做更便宜。你有机会让你的队友不必重新发现已知的东西，或者让他们不必编写已经写好的东西。一些探索是好的。但总有一个门槛，你应该鼓励队友根据任务设定截止日期。当他们通过时，寻求帮助是最好的举措。这也有助于捕获在编写之前会成为推送问题或生产问题的错误。

代码审查也是如此。如果您有技术工作要做，但等待代码审查，则应首先进行代码审查。等待某人审查你的代码是残酷的，特别是如果审查往返很长。如果您坐在上面，工程师将上下文切换到新任务。当他们对代码的记忆很新时，最好做评论。他们将对您的问题提供更快更好的答案，并且能够快速调整他们的拉取请求以准备提交。

鼓励将大型更改拆分为多个拉取请求也很重要。在预先讨论项目时，请务必建议如何拆分它。例如，“第一个将添加 API，第二个将数据发送到客户端，第三个将使用数据呈现新组件。” 这使您可以详细检查每个更改，而无需花费数小时审查并重新审查巨大的拉取请求。如果您认为变更风险太大而无法立即提交，因为它太大而您无法理解其所有后果，那么可以请求将其拆分。您应该确信更改不会删除网站。

即使采取这种态度，您也不会快速审查所有拉取请求。不可能。例如，我的大多数团队都不在我的时区。我在工作时间之外得到了评论，直到我在 10 分钟的工作中开始工作之前，我不会在电脑上查看它们。

我个人认为代码审查和问题是可以中断的。如果我从我们的团队进行代码审查，我将停止我正在做的事情并进行审核。这不适合所有人，因为它是另一种中断类型，老实说，整天打断都很累。随着时间的推移，处理中断对我来说变得更加容易，但是我从几个人那里获得了反馈，但这些反馈并不适合他们。你永远不会擅长它。我不是。不可能。你将变得更好地管理你的纯粹必需品的时间。

## 你的大部分时间都花在帮助初级工程师身上

一个典型的高级工程师是自我导向的。你可以抛出一个无限制的问题，他们会组织起来。他们有时间需要建立共识。他们将技术工作分解成块，并找出需要回答的问题。他们很少会以负面的方式给你带来惊喜。

但是，并非所有人都是高级工程师。您的团队将由初级和高级工程师组成。非常好！初级工程师是一项投资，每个高级工程师都处于这个位置，因为人们投资于他们。没有神奇的算法决定如何在团队中的工程师之间分配时间。但是我注意到一个人越是年轻，我和他们一起度过的时间就越多。

这里有一个推论。确保新工程师知道他们有此选项。明确表示与您联系是正常的，并且这样做不会受到惩罚。我记得在我担任初级工程师时害怕向高级工程师询问问题，所以当他们提出前几个问题时，我总是尽力保持友好。如果他们在办公室就亲自过去，并确保他们的问题得到了充分的回答。如果他们消失了一两天，请检查他们。画出你正在谈论的内容，并在谈完后给他们提供论文。

## 降压停在这里

我的经理曾告诉我，领导者对没有明确所有者的问题负责。根据我的经验，这意味着你应该为许多不合时宜的工作负责，而且往往是不费力的工作，以推动团队前进。

问题是 “什么东西应该容易，但很难？”，这是一个很好的启发式方法，可以在哪里花时间。例如，当搜索体验是一个新团队时，推出新功能是痛苦的。我们从来没有以同样的方式踢过功能，我们不知道我们应该测试哪些组，我们（令人不快）让我们的数据科学家感到惊讶，有时我们忘记在测试时为员工启用内容。所以我写了一个文档，逐步解释了我们应该如何引导从概念到A / B测试的功能，再到启动它们或禁用它们的决定。然后，我们的数据科学家在此过程中添加了大量关于何时让她参与的信息。现在推出功能要容易得多，因为我们有一个手册可以做什么。

这可能会使图片中的工程经理和/或产品经理感到困惑，因为他们也应该默认负责确保工作完成。但这并不像听起来那么严重。想象一下棒球的流行音乐，一个球落在三个人之间。如果每个人都站着不动并看着它落地，那就不好了。如果你们所有人都试图抓住它们会更好（因为抓住它的几率比没有人尝试的要好）。如果你们三个人有一个处理意外问题的系统，那就最好了。常规 1：1 见面和状态更新是解决此问题的好方法，尤其是在开始时。

## 利用传播知识的作用

当团队拥有 Tech Lead 时，他们最终成为活动的中心枢纽。他们将讨论团队中每个项目的设计和审核代码。

如果您阅读了团队在拉取请求中发出的所有代码，您将以加速的速度学习。您将很快深入了解团队的代码库。你会看到有效的技术。您可以询问有关不清楚的事情的问题。如果您还在团队之外进行代码审查，您将了解其他开发人员的新技术，库和技术。这使您能够更有效地为您的团队提供从整个公司学到的知识。

由于您处于这个位置，因此您可以通过团队快速定义和传播最佳实践。一个很好的资源，提供一些代码审查的建议是前 Etsy 员工 Amy Ciavolino 的演示。这是一个很好的团队导向的风格。随意根据自己的风格调整零件。如果你和我一起工作，你会发现这有时与我的不同。例如，如果我有 “您的想法？” 反馈，我更喜欢面对面/ Slack / Vidyo对话。这通常以头脑风暴结束，并创造出比我们任何一个人想象的更好的第三种方法。但这个演讲是一个很好的开始，也是一个强有力的指导方针。

## 日常工作

正如我上面提到的，Tech lEAD 的大部分工作都是中断驱动的。这对团队有利，但它增加了安排自己时间的挑战。在一个轻松的日子里，我将花费一个小时做科技领导工作。但是在一个沉重的日子里，我会得到大约一个小时的时间，而不会因为中断而被吃掉。

因此，很难估计你什么时候会完成一些事情。我和我们的工程经理一起制定了一个运作良好的系统。我只接受了小型，非阻塞或没有截止日期的项目。这对于试图获得最少量流程的团队来说效果很好。这将是对估计超组织的团队的重大调整。

你需要对付随之而来的内疚。你的工作不是要编写最多的代码。你的工作是让团队中的人看起来很好。如果需要做一些重要的事情，而你没有时间去做，你应该委托它。这将有助于整个团队向前发展。

当我决定做什么时，我会大致优先做事：

**内环**：

 - 回答任何 Slack ping
 - 在我的团队频道中帮助任何需要它的人
 - 做任何待定的代码审查
 - 确保团队中的每个人都有足够的工作在一周的其余时间
 - 做任何流程/组织工作
 - 项目工作

**一天一次**：

 - 检查性能图表。调查（或委托）主要回归到我们可能已经影响的事情。
 - 检查所有 A/B实验。对于新实验，请查找存储错误，性能问题（或意外收益，更可能是错误）等。

**每周一次**：

 - 查看 bug 积压，确保一个主要错误没有滑过裂缝。

## 这对工程师经理意味着什么

许多团队没有 Tech Lead，但每个团队都需要技术领导才能有效运作。这是工程管理人员的行动呼吁，以检查他们团队的动态。你团队中谁在执行这项工作？他们是否因此获得奖励？特别是，寻找代表性不足的群体的成员，由于无意识的偏见，他们可能因编写较少的代码而受到惩罚。

想象一下工程师团队。上面列出的职责可能属于以下类别之一：

**指定的技术负责人处理工作**。如果您的团队属于这一类，那就太好了！确保履行这些职责的工程师或工程师得到认可。

**除了他们现有的工作之外，有人对此负责**。根据工程经理对领导工作的看法，这对工程师来说可能是一种祝福或诅咒。他们的工作可能会受到赞赏。但也有可能人们只是目睹他们的编码输出下降，而没有认识到推动团队前进的工作。如果你的团队中＃#2 大部分都是正确的（技术主管没有正式化，而且有些工程师负责推动团队前进，而牺牲自己的 IC 工作），那就问问自己：他们是否正在接受评判只是为了他们的工作？或者他们是否因为他们启用的所有传递性工作而获得奖励？

**有些人会这样做，但他们经常被忽视**。这个类别的工作仍然有效，但有系统的阻截者。如果没有人拥有代码审核，则需要很长时间才能审核代码。如果没有人拥有代码质量，你的代码库将成为瑞士未发布的破碎标志。

**没有人对他们负责**。在这个类别中，有些事情根本无法完成。例如，如果没有人默认负责成为代表性不足群体的盟友，那么很可能只会将其丢弃在场内。这种情况是分形的：如果我们将球放在小组级别上，我们就会在个人和公司范围内放弃球。

## 结论

为您的团队指定 Tech Lead 是有价值的。他们将创建和推广最佳实践，成为团队中的重点人物，并消除工程障碍。此外，这项工作可能已经由某人完成，因此正式承认承担此责任的人员非常重要。

正式承担这一角色也有很多价值。它允许您利用您的时间推动组织向前发展，并使您能够影响整个团队的工程。

如果您正在接受这项工作，并且您不是正式的 Tech Lead，那么您应该与您的经理讨论此事。如果您想成为 Tech Lead，请与您的经理（或 Tech Lead，如果您有一位！）谈谈您可以承担的任何责任。