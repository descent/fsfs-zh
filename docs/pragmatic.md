## Copyleft：务实的理想主义<!--(pandoc) {#pandoc_pragmatic}(pandoc)-->

> Copyright © 1998, 2003 自由软件基金会

一个人做出的每个决定都取决于这个人的价值观和目标。人们可以有很多种不同的目标和价值观；声誉、利益、爱情、生存、快乐和自由，其中有一些目标只有一些优秀的人才可能拥有。当这个目标是一种原则时，我们称之为理想主义。

一个理想主义的目标激励着我在自由软件上的工作：传播自由与协作的理念。我想鼓励自由软件的传播，取代阻碍合作的专有软件，从而使我们的社会更加美好[^pragmatic-1]。

这就是 GNU 通用公共许可证被写成 Copyleft 的根本原因。所有代码被添加到由 GPL 许可证保护的项目必须是自由软件，即使它被放进一个单独的文件里。我使我的代码在自由软件里可用，并且在专有软件里不可用，目的是为了鼓励其他写软件的人也使它自由。我想既然专有软件开发者们利用版权来阻止我们分享，我们合作的人可以利用版权给予其他合作者一些对于他们自身的好处：他们可以使用我们的代码。

不是所有使用 GNU GPL 的人都有这样的目标。许多年以前，我的一个朋友被要求在非 copyleft 的条款下重新发布一个 copyleft 的程序。他大概是这样回应此事的：“有时我从事于自由软件，而有时我从事于专有软件——但当我从事于专有软件时，我希望得到*回报*。”

他很乐意与一个分享软件的社区来分享自己的成果，但似乎没有理由向那些偏离我们社区限制的商业产品给出一个发布版。他的目标不同于我的，但是他觉得 GNU GPL 对他的目标也有用。

如果你想完成某件事情，光靠理想主义是不够的，你需要选择一种实现你的目标的方法。换句话说，你需要更“务实”。GPL 许可证务实吗？让我们看看它的成果。

就拿 GNU C++ 来说吧。为什么我们会有一个自由的 C++ 编译器呢？仅仅因为 GNU GPL 规定它必须是自由的。GNU C++ 是由起源于 GNU C 编译器的一个工业协会 MCC 开发的。MCC 通常尽可能使它的作品专有化。但是他们让 C++ 前端自始至终是自由软件，因为 GNU GPL 规定这是发布它的唯一方式。C++ 前端引入了很多新的文件，但是因为它们要链接到 GCC 上，所以 GPL 能约束它们。并且这样做对我们社区的益处是显而易见的。

再说说 GNU Object C。NeXT 公司最初想把这个前端变成专有的；他们打算以 `.o` 文件的形式发布，并让用户使用 GCC 的其余部分来链接他们，想这样能绕过 GPL 的要求。但是我们的律师说这不能躲过这些要求，那是被禁止的。所以他们使 Objective C 前端成为了自由软件。

这些例子发生在好多年前，但是 GNU GPL 一直持续带给我们更多的自由软件。

许多 GNU 库遵循 GNU 宽通用公共许可证（GNU Lesser General Public License），但不全是，Readline 就是一个使用普通 GNU GPL 许可证保护的 GNU 库，它实现了命令行编辑功能。我曾经发现一个非自由程序被设计为使用 Readline，并告知程序开发者这是不允许的。他本可以从程序中移除命令行编辑功能，但他实际所做的是让这个程序基于 GNU GPL 许可证重新发布。现在这个程序是自由软件了。

这些写代码改进 GCC（或者 Emacs、Bash、Linux 或其它遵守 GPL 的程序）的程序员们经常被公司或者大学雇佣。当程序员想把他们的改进回馈给社区，从而在下一次发布能看到他的代码时，老板可能会说，“到此为止，你的代码属于我们！我们不想分享它；我们已经决定把你的改进版本添加到专有软件产品里了。”

这时候 GNU GPL 就会出来拯救你的成果了。程序员告诉老板这样的专有软件产品是侵犯版权的，从而老板会意识到他只有两种选择：把这些新代码以自由软件的形式发布，或者什么都不做。大部分时候老板会让程序员按照他一直所想的来做，把这些代码加到下一个发布版。

GNU GPL 不是“和事佬”，有时它也会对人们想要做的一些事情说“不”。有一些用户说这是一件糟糕的事情——GPL 许可证会“拒绝”一些“需要被带进自由软件社区的专有软件开发者”。

但是我们并没有把他们拒绝在我们的社区之外；是他们选择的不加入。他们使软件专有化的决定也是在我们社区之外的决定。融入我们的社区就意味着与我们的合作；如果他们不想加入，我们就不能“把他们带入我们的社区”。

我们*能*做的是提供给他们一个加入的动机。GNU GPL 许可证被设计用来从我们现有的软件中产生一个动机：“如果你想让你的软件自由化，你就可以使用这个源代码”。当然，虽然不会赢得一切，但会赢得一些时间。 

专有软件的开发不会对我们的社区有所贡献，但它的开发者们经常想从我们这里得到资料。自由软件用户可以为自由软件开发者提供一些自我暗示——认可和感谢——但是当一个商人告诉你，“只要让我们把你的软件包放进我们的专有软件中，你的程序会被成千上万的人使用！”，这是非常引诱人的。这个诱惑是很有力的，但从长远来看，如果我们坚持这一点，最好离远点。

当这种诱惑和压迫通过迎合专有软件策略的自由软件组织间接到来时，它们就更加难以辨别。X 联盟（与他的继任者，Open Group）提供了一个例子：由开发专有软件的公司建立，他们努力了十年来说服程序员们不要使用 Copyleft。Open Group 曾经试图使 X11R6.4 变为非自由软件[^pragmatic-2]时，我们当中很多人抵抗住了这个压迫，很高兴我们做到了。

在 1998 年 9 月，X11R6.4 以非自由发行条款发布的几个月之后，Open Group 推翻了自己的决定，并且用 X11R6.3 使用过的非 copyleft 的自由软件许可证重新发布。感谢你，Open Group——但是这个后来的逆转并不能改变我们已经得出的结论，他们依旧*有可能*加入限制。

从实际来讲，考虑更长远的目标会更加坚定你反抗这种压迫的信念。如果你把你的思想专注于自由和可以待在公司建设的社区，你会找到这样做的动力。“坚定信念，否则你会上当受骗”。

如果有愤世嫉俗的人嘲笑自由，嘲笑社区……如果“硬鼻子的现实主义者”说利润是唯一的理想……忽略他们就好，继续使用 Copyleft。

[^pragmatic-1]: 参见[《为什么使用 Copyleft？》](why-copyleft.md)一文

[^pragmatic-2]: 更多相关信息，请参见[《X Window 系统的陷阱》](x.md)一文
