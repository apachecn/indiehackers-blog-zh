# 以个人创始人的身份建立每月 3000 美元的评论服务

> 原文：<https://www.indiehackers.com/interview/building-a-3-000-mo-review-service-as-a-solo-founder-e1ddcc26ac>

## 你好！你的背景是什么，你在做什么？

嘿！我是 Kevin Ohashi，我是[回顾信号](http://reviewsignal.com/webhosting)的创作者。我的背景是计算机科学和商业教育的结合。我在佛蒙特大学学习经济学和计算机科学，然后去了瑞典隆德的研究生院，获得了两个硕士学位，一个是企业家学位，另一个是国际营销和品牌管理学位。

审查信号是所有诚实的虚拟主机审查。它利用人们在 Twitter 上分享的大量观点作为评论的来源。

在我开始 Review Signal 之前，我从事虚拟主机业务大约有十年了，仍然没有一个评论网站赢得了业内人士的一点点信任。因此，我的目标是创建一个消费者评论网站，通过让评论完全透明来建立信任，而不是简单地根据谁付费最高来排名。

很难衡量我做得有多好，但根据一家公开发布净推介值的公司的说法，我从这些公司那里得到的罕见一瞥告诉我，我的算法非常密切地跟踪着[的净推介值](http://reviewsignal.com/blog/2015/08/19/liquidweb-nps-scores-vs-liquidweb-review-signal-rating/)。

今天，Review Signal 是世界上最大的虚拟主机评论网站，至少是一个数量级，可能是两个数量级，每月收入大约在 3000-4000 美元之间。

[![Review Signal](img/6cee10b29270a6e11970719fb2d9eea1.png)](http://reviewsignal.com/webhosting) 

## 是什么促使你开始使用 Review Signal？

我的国际营销与品牌管理学位论文演变成了[的评审信号](http://reviewsignal.com/webhosting)。我的论文是关于使用推特来预测电影票房的，而且效果很好。我在几个月的时间里收集了大约 500 万条推文，发现当结合情感分析时，这些数据的预测能力非常强。对于那些不熟悉情感分析的人来说，这完全是为了弄清楚文本的语气，通常是好是坏。

毕业后，我搬回了美国，决心开创自己的事业，并开始从事《评论信号》的工作。我选择关注虚拟主机评论有很多原因。我之前提到过一个大问题，即竞争基本上都是付费游戏联盟垃圾，将消费者卖给出价最高的人。这也是有意义的，因为我对这个领域非常熟悉，品牌通常是全球性的，几乎所有的品牌都有联盟计划。

老实说，我并没有对这个想法进行过多的验证。我觉得我非常了解这个空间，也知道需要一个诚实的托管评论网站。

## 构建最初的产品需要什么？

构建[审查信号](http://reviewsignal.com/webhosting)是一个长达两年的过程。对我来说，最大的挑战是技术方面。我花了几个月的时间试图找到一位技术联合创始人，他会给开发团队带来更多技能，让我专注于产品和营销。我在寻找中失败了，最终决定只是成为技术创始人。

我从硕士论文中学到了相当多的东西，但远远不够。我唯一的专长是了解主机行业，并且是一名优秀的软件开发人员。其他的一切我都不得不自学，因为我找不到任何现成的对我所设想的足够好的东西。

几乎所有的 tech powering Review 信号都是用 PHP 从头开始构建的。我确信许多技术读者在问，“为什么是 PHP？”鉴于 Python 中有成熟的、受支持的自然语言处理任务库。我的回答是:我不知道 Python。那时我已经写了大约十年的 PHP，我对它非常满意。

只要您能解决他们的问题，大多数客户并不关心底层技术。

TweetShare

所以我从头开始编写了所有需要的库，包括错误地实现了一个贝叶斯分类器，因为当时我并没有真正理解它。(是的，我后来重新做了——我想是正确的。)

我唯一使用的有意义的第三方库是用于博客的 WordPress 和用于处理 Twitter 的流媒体 API 的库。对我来说，最大的挑战是我以前从未建造过如此庞大复杂的东西。我根据当时对我有意义的东西做出架构决策，并尽可能多地从密友那里获得反馈。

我也试着设计它，因为“它能有多糟糕？”悲剧地糟糕。谢天谢地，我在纽约的一次 YCombinator 活动中遇到了亚历克西斯·奥哈尼安，他特意花了一个小时和我坐在一起，并给了我反馈。

我从中吸取的最重要的东西是设计有多糟糕，我真的需要花一些时间和金钱来修复它。一个拥有糟糕用户界面/UX 的伟大产品不会给任何人带来任何好处。从一个我尊敬的人那里听到的话让我明白了这一点。我找了三个设计师，才找到了和我一起设计你今天看到的这个设计的[JR . Harrell](http://drawnn.com)。

## 你是如何吸引用户和发展评论信号的？

很多人说，“不要把注意力放在发布上——这不重要。”但是对于[审查信号](http://reviewsignal.com/webhosting)来说，这关系重大。2012 年 9 月，我在 [TechCrunch](https://techcrunch.com/2012/09/25/web-hosting-reviews-are-a-cesspool-review-signal-wants-to-fix-that/) 上发布了评论信号。我可以自信地说，那篇文章单枪匹马地将《评论信号》变成了一门生意。TechCrunch 比我有更好的搜索引擎优化。这篇文章发表后，在互联网上最具竞争力的关键词中，它跃居谷歌搜索结果的首位。(我们说的是每次点击 20 美元的领域！)

因此，我不仅获得了这种免费的、非常有价值的流量，用户还被告知，我的网站是合法的，而其他人都不是。事实是，我真的很幸运，我的邮件是由一位编辑转发的，这位编辑是我 6 个月前认识的，他对这个话题感兴趣，但可能不会打开我的邮件，除非是他的编辑转发的。我甚至[写下了那次经历](http://kevinohashi.com/27/11/2012/reverse-engineering-startup-press-how-and-why-techcrunch-covered-my-launch)，试图找出它发生的原因。

每一段感情都可能对我产生巨大的影响…所以我努力最大化我的意外收获的潜力。

TweetShare

运行 Review Signal 最具挑战性的部分是，如果我做好我的工作，我的访问者应该永远不会回来。他们选择了一家很棒的公司，从此幸福地生活在一起。如果我没有做好，那么用户就不应该回来，因为我辜负了他们。所以几乎我获得的每个顾客都是全新的。这意味着，无论人们在哪里寻找关于虚拟主机的建议，你都要在场。

我有适度的谷歌排名。我花很多时间在脸书、论坛、Reddit 等特定的社区上。，努力帮助他人，并提及我的信息何时可能有助于帮助他们。这是垃圾邮件和帮助之间的微妙平衡，我尽量不越过那条线。

我营销策略的另一大部分是创造非常高质量的内容。我写过的最成功的一系列内容是名为 [WordPress 主机性能基准](http://reviewsignal.com/blog/2016/09/14/wordpress-hosting-performance-benchmarks-2016/)的年度分析。这是我在 WordPress 虚拟主机领域的每一家虚拟主机公司进行的一系列长达数月的基准测试。

如今，在运行了四年之后，许多公司开始接近我，并信任我的基准。我测试过企业级计划，我认为其他人都没有机会进行基准测试。我得到了这个机会，因为我尽可能透明地做事，这样每个人，公司和消费者，都可以看到所有这些选项是如何相互叠加的。

我只收到过一个公司对我如何进行测试的投诉，这是一种误解，因为它们只针对一个国家，而我是从全球角度进行测试的。考虑到他们的目标观众，他们没有表现出他们认为应该表现的那样好。但是误解创造了改进的空间，这是好的一面。

专注于特定领域的另一个好处是，我的内容在该领域受到了很多关注，并且在我发布时得到了相当多的媒体关注，因为我已经随着时间的推移建立了关系。

我的总体内容策略是，我试着写一些重要的东西，而不是人们已经读过一千遍的老调重弹。我不确定这是否是最好的财务策略，但在关心这种东西的一小部分人中，这无疑树立了我的品牌。我写了很多关于这个行业的不好的事情，但是很少有人关心。也许对我来说这只是一种宣泄，或者极少数在乎的人是重要的关系。可能两者都有一点。

对我来说，表现最好的内容是旨在帮助消费者购买或实现某些目标的文章。有时很难知道哪些文章会做得很好，但我只是试着写对我来说重要的东西，并尽我所能传达为什么它很重要。我与业内和业外的朋友一起测试想法和早期草案，看看哪些想法和草案真正引起了兴趣，以及与谁一起。

你越了解人们，你就能更好地做很多事情。

TweetShare

这对于获得反馈/想法以及获得反馈者的认同有很大的好处。如果那个人碰巧很有影响力，他们更有可能分享他们觉得自己有所贡献的东西。只要记得对帮助你的人说谢谢，并在你出版时让他们知道。

由于 Review Signal 是一个人的操作，所以我也尽可能地尝试自动化。我已经建立了许多定制的营销自动化工具，并尝试使用现有的工具，如 [IFTTT](http://ifttt.com) 来帮助我尽可能高效地利用时间。

我最喜欢的工具之一，我创造了命名为利基铅发电机。它扫描高价值的线索——在这种情况下是关于虚拟主机评论的对话——并帮助我吸引他们。它不会一直试图检查所有的东西，而是为我做繁重的提升和过滤工作，只给我它确定的最高价值的潜在线索。我知道它有效，因为我确实因为它写了关于 Review Signal 的文章，并跟踪了直接归因于它的销售。这让我有更多时间专注于创作内容，并与帮助传播内容的记者/博主/有影响力的人建立关系。

我从不断增长的评估信号中得到的最大收获是，我不知道自己在做什么。我只是不断尝试不同的东西，看看什么有效。如果成功了，再做一次，试着改进它，试着扩大它。如果不行，试着改变它，试着找出它为什么不行。有时候扔出去还行，有时候值得试探几次。对于这些我没有什么神奇的公式。我试着看分析，看看我的流量来自哪里，哪一个转换最好。

我也很喜欢和任何谈论或链接到 Review Signal 的人交谈。如果我看到有人写评论信号，通常我会尝试联系那个人，展开对话。为什么？因为他们已经在为我辩护了，我要感谢他们。

有时他们成为朋友，有时什么都没发生。有时他们不断给我送新人。每一段感情都可能对我、我的事业或我的生活产生巨大的影响；所以我试着最大化我的意外收获的潜力。

## 你的商业模式是什么，你是如何增加收入的？

[点评信号](http://reviewsignal.com/webhosting)的商业模式相当简单。它从附属链接中赚钱。大多数虚拟主机公司都有会员计划，任何人都可以注册。代销商只需在他们的网站上放一个特殊的链接，当有人点击并购买某样东西时，就可以赚取佣金。审查信号是签署了几乎每一个可用的附属计划，例外是有问题的服务语言条款，可能不允许负面的事情对公司说。

商业模式从一开始就没有改变。Review Signal 从上线那天就开始赚钱了。它在第一个月(很短的一个月)赚了 52.38 美元，第一个整月赚了 535 美元。

收入会有很大的波动，因为大量销售可以赚取数百美元的佣金。但我希望平均每月能挣 3000 美元左右。今年迄今为止最好的一个月是 5000 美元左右。希望这成为一种新的常态，但在接下来的一个月里，它立即回到了 3000 美元左右。

只要我把针向前移动一点点，我就在进步。

TweetShare

因为这是代销商销售，我很难控制我的访问者转化。我有关于访问者的代理信息，如页面/访问，在网站上的时间等。但是大多数联盟计划不会让我实际跟踪哪个确切的访问者转化成了销售。在我把它们发送到网站上几个月后，它们也可能转化为销售(附属 cookies 可能会持续几个月甚至更久)。

我试着不去担心它，但是在我内心深处，我总是在想我今天、这个星期或者这个月做了多少销售。但是答案一般都是随机的。今年最好的一个月实际上在上半年开始就变成了最差的一个月，然后就爆发了。为什么？我不知道，也永远不会知道。欢迎来到我的生活，作为一个很少或根本没有控制跟踪我的销售。这是一个无缘无故失眠的好方法。

如果你正在建立一个联盟网站，意识到最重要的是你获得流量的能力。所以你最好至少擅长以下一件事:

*   搜索引擎优化
*   搜索引擎营销
*   内容创作
*   获得媒体/营销
*   转换优化

实际上，你可能需要做大部分/所有这些事情。每个洞都可以挖得很深，你可以把所有的时间都花在任何一个兔子洞上。我花了大部分时间专注于搜索引擎优化，内容创作和新闻/营销。

我不认为试图过于努力地推动销售对于一个中立的评论网站来说是一个很好的形象，所以我不会太专注于转化优化。SEM 对我来说太贵了，无法竞争。我确实在寻找其他付费广告机会，比如像 [Outbrain](http://www.outbrain.xn--com-kn0a) 这样的服务，将我最好的内容更广泛地推向目标受众。

以下是我今年预计的月收入:

| 月 | 维护、修理和更换 |
| --- | --- |
| 一月 | 2730 |
| 二月 | 3646 |
| 三月 | 4893 |
| 四月 | 2754 |

## 你未来的目标是什么，你打算如何实现它们？

从技术方面来说，我想重新设计[评论信号](http://reviewsignal.com/webhosting)，并为用户开发更多的互动工具来探索我收集的数据。我认为它目前在呈现数据方面做得不错，但是还有很大的空间来创建更强大和有趣的工具。

我也想把它扩展到其他领域。但是有一些非常大的挑战，因为我建立和训练我的系统的方式。这可能需要引入更多的开发人员来重建大量的系统。

独自工作时，你需要学习如何提高效率，而且经常需要欺骗自己提高效率。

TweetShare

从业务方面来说，SEO、创造内容、口碑是我营销评论信号的三个主要方法。我仍然没有在首页上排名很多最大的关键词，如“虚拟主机评论”。我想排名第一的关键字，但竞争是非常根深蒂固的，许多使用黑帽技术。

当我看到创造独特和有价值的东西的机会时，我会继续创造内容。口碑通常来自意识，所以我将继续在各种在线社区中参与并帮助人们，并慢慢说服更多人了解 Review Signal 的使命。

我不抱任何幻想。复习信号不太可能大爆发。自推出以来，它已经慢慢成长了四年。我的目标人群通常是一次性研究和购买产品的消费者。因此，可持续发展的唯一真正途径是创造一个更广泛的营销渠道，并不断探索新的潜在客户来源。每一篇文章、链接和搜索引擎位置都会慢慢被争取，随着时间的推移，总的来说，希望评论信号继续增长。

## 你面临的最大挑战是什么？如果你必须重新开始，你会做什么不同的事情吗？

绝对最大的挑战是如何面对自己。[回顾信号](http://reviewsignal.com/webhosting)从一开始就是一个人的操作。有时候我会非常积极地去努力，而且我会取得很大的进步。很多时候，我不想看它，宁愿做别的事情。

6 年后，倦怠总是潜伏在我脑海的某个角落。我不想再一个人开公司了；对一个人来说太多了。(旁注:这不代表我不会。也许这只是我的受虐狂。)

从技术角度来看，构建整个系统是我做过的最大的学习经历和承诺。我很早就做出了我想重做的决定，因为我已经学会了更好的做事方法。但是我认为重构代码没有太大价值，除非绝对必要。这也限制了现在可以做的事情，比如寻找新的利基市场。

你的技术可能看起来很酷，但它真的归结为营销。

TweetShare

如果我不得不重新开始，我可能会使用 Apache Storm 来构建系统，这是我在发布几年后学到的。我也可能会考虑使用和测试一些现有的库，而不是从头开始构建一切。

我可能会尝试筹集一些资金，并聘请另一名开发人员与我一起工作。我在机器学习和自然语言处理方面完全是自学的。如果有人在我设计系统所依赖的关键领域有更多的经验，那就太好了。

自己做这一切的一线希望是我什么都懂。这个心智模型完全包含在我的头脑中——对于 Review Signal 的任何部分在做什么，我都不会感到困惑。这让我可以很快地改变事情，而不需要解释任何事情，也不需要向别人寻求解释。

但这是一把双刃剑，因为这意味着我必须这样做。也就是说我没有做别的事。

## 你最大的优势是什么？有什么特别有用的吗？

我曾经拥有并且现在仍然拥有的为数不多的优势之一是，在虚拟主机评论行业，几乎没有人是诚实的。你可以看看这个领域中一些真正知名的名字(包括 Drupal.org 和 WordPress.org)，它们要么是伪装成推荐的赤裸裸的广告，要么是这个过程非常不透明，鉴于被推荐公司和推荐人之间错综复杂的财务关系，这些推荐是值得怀疑的。

大多数了解这个领域的人都知道情况有多糟糕，但他们没有任何可以推荐的东西。我正在慢慢地将有影响力的人转变为相信和信赖我的数据。一些人甚至不怕麻烦地写下自己的经历。用正确的方式做事是我最大的优势。

独自工作时，你需要学习如何提高效率，而且经常需要欺骗自己提高效率。我每天的目标是完成一件事。不管事情是大是小，如果我完成了某件事，我那天就取得了进步，我会感觉很好。

有些日子收获颇丰。其他时候，它可能是像发送电子邮件一样琐碎的事情。只要我把针向前移动一点点，我就在进步。

我还想谈谈令人惊叹的共同工作空间，它使我能够建立和启动 Review Signal。这可能是美国最古老的联合工作空间，位于华盛顿特区的 Affinity Lab。我于 2011 年加入 Affinity Lab，它成为我在 DC 的家，也是我与当地创业社区的联系纽带。这让我意识到真正的合作能产生多大的影响。我在那里建立了最牢固的职业和个人关系。那里的同事在构建和发布 Review Signal 的许多方面都帮助了我。我遇到了我的律师、公关人员和许多帮助我解决问题的技术朋友，这里仅举几例。

如果说我成功的最大决定因素是什么，那就是在亲和实验室。我周围的人都在平行的创业旅程中，但都愿意合作和互相帮助。与合适的人和合适的环境在一起真的让构建评审信号成为可能。

## 对于刚刚起步的独立黑客，你有什么建议？

我想对任何试图开始自己项目的人说的第一句话是，要有钱。如果你要全职做某件事，你需要 runway，也就是银行里的钱。

如果你是兼职，有一份可以支付账单的日常工作是必要的。但我不喜欢兼职项目，我真的想成长。我发现我的大脑不能很好地分散注意力。如果我在做一个客户项目，因为我有时会做咨询，即使我没有直接做这个项目，我的大脑也会想着这个项目。这些额外的大脑循环并没有被用来推进我的项目，而这正是我有时能获得最佳想法的地方。

当然，拥有这样的选择是一种奢侈。但是，如果可能的话，我想把全部时间花在我的项目上，并试图找到一种方法来实现它。为了发射复习信号，我搬回家住了几年，以便开发它并省钱。

我学到的另一个教训是，你的技术可能看起来很酷，但它实际上是营销(除非你正在为其他开发者构建一些东西)。如果你的产品足够好，问题是你能不能找到客户。这些天，我花在开发上的时间很少，可能超过 90%的时间都花在营销上，或者一些对我的营销有帮助的事情上。只要您能解决他们的问题，大多数客户并不关心底层技术。

我读过的最喜欢的书之一是丹尼尔·卡内曼的《T2 思考，快与慢》。是关于卡尼曼在行为经济学领域的研究。它教你人类的大脑如何运作和处理信息。

它可能不直接适用于经营你的创业公司，但如果你曾经销售/展示/推销/营销你的产品，那么你就接触到了书中提到的一些东西。它不是关于如何做具体事情的指南，而是进入人类思维的指南。你越了解人们，你就能更好地做很多事情。

## 我们可以去哪里了解更多？

*   [评论信号网站](http://reviewsignal.com)
*   [回顾信号博客](http://reviewsignal.com/blog)
*   [@推特上的 review signal](http://twitter.com/ReviewSignal)

我很乐意回答人们可能对 Review Signal 或初创公司提出的任何问题。

首先，我将回答我收到的最常见的问题之一:人们不都是在不开心/生气/心烦的时候发关于一家公司的微博吗？

是也不是。每年我都会花一些时间回顾当年的数据并进行分析。2016 年，我为《信号评论》增加了约 36，000 条新评论。评论总数的 49.6%是正面的。所以没错，人们确实写的负面的东西比正面的多。然而，52.1%的独特评论是正面的。

这告诉我们，说好话的人比说坏话的人多。但是写差评的人写差评的频率更高。人们担心的另一部分是这些倾向可能会使我的数据产生偏差。答案也很简单:我的排名是相对的。没有一家公司的客户天生或多或少会写好或坏的东西。所以我的系统在同样的规则下公平地对待每个人；它只是适应了人类的本性。

—[<picture id="ember5277808" class="user-avatar ember-view user-link__avatar">![](img/82bd3bb4769a3aa1cd13889ee7c0fa91.png)</picture>ohashi](/ohashi?id=BRtkWsEn3RQyME7K47rooWNjv1A2)，审核信号的创建者

## 想像 Review Signal 一样建立自己的事业？

你应该加入独立黑客社区！🤗

我们是几千名创始人，互相帮助建立有利可图的业务和副业。来分享你正在做的事情，并从你的同事那里获得反馈。

还没准备好开始使用你的产品吗？没问题。这个社区是一个认识人、学习和实践的好地方。随意[随便浏览](/)！

—[<picture id="ember5277813" class="user-avatar ember-view user-link__avatar">![](img/82bd3bb4769a3aa1cd13889ee7c0fa91.png)</picture>考特兰艾伦](/csallen?id=ibTLPyjwVebnZjMGKvz6ztarnuV2)，独立黑客创始人

10votes