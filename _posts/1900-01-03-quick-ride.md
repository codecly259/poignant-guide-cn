---
title: "快速(有希望且无疼痛的)上手Ruby(与卡通小狐狸一起)"
permalink: book/chapter-3.html
layout: chapter
sections:
- - section1
  - 语言，我是说语言
- - section2
  - 演讲部分
- - section3
  - 如果我还没有把你像孩子一样对待
- - section4
  - 一个例子来帮助你成长
- - section5
  - And So, The Quick Trip Came To An Eased, Cushioned Halt
---

![The foxes show up.](../images/the.foxes-1.png "The foxes show up.")

Yeah,就这两只。有点哮喘，我吸点药先，马上回来。

![Foxes in boxes.](../images/the.foxes-2.png "Foxes in boxes.")

友情提示，看本章前最好先准备条手巾，方便擦泪嘛。

我们就快速通览下整个语言。就像拿个火柴盒，尽可能快的划光里面的火柴 -V-

<a name="section1"></a>

## 1. 语言，我是说语言

![Our friends, those two helpless foxies, finally realize the gravity of their
predicament.](../images/the.foxes-3.png "Our friends, those two helpless foxies,
finally realize the gravity of their predicament.")

凭良心说话，我不会把ruby当成一门*计算机*语言。看得出，计算机语言首先指的就是操作
计算机的语言——计算机是它的国度。我们程序员则是移民过来的外国人，为我们的世界做翻译。

不过，你觉得该怎样称呼这样的语言，你用这门语言的词汇表达文法表达自己的想法，
用它直接来思考？这能是计算机语言么？这个计算机做不了，这是我们的语言。

我们没有必要迷信*计算机*语言这样的说法，*代码民工才这么说*。它是我们思维的语言。

**把它大声念出来**

{% highlight rb %}
5.times { print "Odelay!" }
{% endhighlight %}

念单词，先无视标点符号（如引号，括号）什么的。这几个标点给单词赋予了含义，
帮助我们理解作者的本意。所以我们这么念：*打印"Odelay!"5次*

行如其文。Beck那[突变的西班牙][1]感叹句就会在屏幕上打印五遍。

**把它大声念出来**

{% highlight rb %}
exit unless "restaurant".include? "aura"
{% endhighlight %}

这是个简单的检查。我们的程序会**退出**（程序将要结束），**除非**这单词**restaurant**里面包含
（也就是**includes**）单词**aura**。好，再用英语来一遍：*Exit unless the word restaurant includes the words aura*
（*除非单词restaurant包含单词aura，否则程序退出*）。

见过哪门语言有这么用问号的没？ruby使用了些标点符号（如感叹号和问号）来提升代码的可读性。
就像上面的代码，我们既然是对代码提问题，那为啥不写的更清楚点？

**把它大声念出来**

{% highlight rb %}
['toast', 'cheese', 'wine'].each { |food| print food.capitalize  }
{% endhighlight %}

好吧，这段代码不如前两个那么像英语那么好读，不过我依然建议你念一遍。
Ruby有时是读着像英语，有时更像简化版英语。把上面的代码翻译成英语就是：
*With the words ‘toast’, ‘cheese’,and ‘wine’: take each food and print it capitalized*
（*把单词'toast','chees'和'wine'：每个食物以首字母大写打印出来*）。

然后电脑很有礼貌地回答道：'Toast','Cheese'和'Wine'。

这里你可能感兴趣，这些单词是怎么组到一块儿的。Somtchkkiss同学问了，这几个点和括号
是什么意思？我将要在下一节讨论各种*词性*。

目前为止你需要明白的就是，Ruby代码都是句子。这句子不一定是英文，而是表达你想法的
少许单词和符号组合。这些句子放到一起，可以编成书，可已编成论文，也可以编成小说。
这小说可以给人看，还可以给电脑看。

<div class=sidebar><aside>
{% capture sidebar %}
## 关于这本(辛酸的)指南的商业使用

这本书使用知识共享协议发布，允许没有限制的商业使用这些文字。基本上，这意味着你可以
出售这些盗版我的书来获得收入。我相信我的那些读者（以及他们周围的世界）会来宰我。
把那些蹩脚的复印版装上久经考验的剪纸艺术作为封面。

朋友，法律是不值得头疼的。所以我是支持经过授权的盗版。任何想要读这本书的人都应该可以读到。
任何人想要卖这本书或者由这本书衍生出其他的版本，我荣幸之极。

我为什么要钱呢？<span class="caps">忽略其他所有侧边栏</span>:
我已经失去了想成为富裕笨蛋的愿望。听起来挺残忍，但是我们喜欢我的小黑白电视，
也喜欢我的悬挂式塑料灯。我不想成为一个职业的作家。现金不能激励我，那毫无意义。

所以，如果钱对我来说不意味着什么，为什么要在你做了商业实践之后又来狠狠地压碎我的灵魂
然后又扔下我一个人使用乌黑的铁肺喘息？哦，使用我的作品然后来讽刺我！该死的！尖酸刻薄的男孩！

为了解释我的意思，这里有一些可以杀死我的意志并强迫我重新思考生存意义的秘密内容。

**<span class="caps">想法一</span>: 大<span class="caps">烟草公司</span>**

买一个烟草公司。用我的卡通小狐狸燃烧起一股带侵略性的广告活动。
以这个广告牌作为开胃菜：
![Addiction is like Pokemon!](../images/the.foxes-0a.png "Addiction is like
Pokemon!")

把目标市场定位为儿童和气喘病患者。然后，一旦事情进展顺利，那些
知道**真相**的人们就开始揭发我和我那农场上漆黑的狐狸。

> **明智的行家控制城市的荒野**：他称自己为幸运的尸体。

> （拉起窗帘，露出轮床上灰色的尸体）

> **行家**: 有些尸体并没有那么走运.

> （不稳定的放大。叠加卡通狐狸成为Willy Wonka潜意识上的心灵之旅。）

哟，为什么你非要弄这样烟雾缭绕，就像那福尔摩斯一样？

**<span class="caps">想法二</span>: 嘿, <span class="caps">团队激励</span>**

如我所说，开始卖我的盗版书，但是腐败我的文字。这些改变了的副本将包含大量的
公开（和诽谤）引用政府机构，如美国执法官和五角大楼。你可以让我看起来想一个
彻底的叛徒。就像我有这些计划一样：杀害有些不和人意的美国政府或五角大楼的官员。

我并不是说美国执法官或者五角大楼的官员有什么不和人意的地方。是的，我不是那个意思。

哦，废话。

哦，废话。哦，废话。哦，废话。

把灯关掉。下来。

**<span class="caps">想法三</span>: 广告牌, <span class="caps">第二部分</span>**

关于哮喘的直接乐趣？

![Call it a puffer! ROFL!](../images/the.foxes-0b.png "Call it a puffer! ROFL!")

**<span class="caps">想法四</span>: 亚力克 <span class="caps">鲍德温</span>**

把这本书改编成电影。然后，你知道，我是这本书的一个角色，你可以找一个像Alec Baldwin
的演员来演我。他正在职业生涯一个困难时期。

你可以使他看起来像我一样在吸毒品。像我一样疯癫。像我一样把人们锁在摩托车房间，
让他们穿着面包做的衣服，然后一直放火烤他们。是的，像我这样把人们*烘焙*成衣服。

你可以制造一个巨大的模具，把人们赶到里面去。然后，我倒入所有的面团开始烘烤，
直到面团已经上升，他们已经几乎死亡。而当摄制组把我请到美国早间新闻节目时，
他们会问，“那么，在你制作书的过程中你雇了多少员工呢？”然后我回答道，“一打面包师！”
并爆发出疯狂的大笑声，这将迫使观众举起手来捂住耳朵。

当然，在我疯狂挣扎的时候，我将向世界宣战。面包人将要参加相当多的战斗。直到美国执法官
（或者五角大楼）设计一个巨大的猴子大脑机器人（由Burt Lancaster饰演）来和我作战。

在这里你将使我看起来完全就像一个瘸子一样。我不仅要牺牲所有的面包人（星河战队）以
拯救自己，我不仅要像一个懦夫一样从巨猴大脑手里逃脱，而且当我勉强的逃离时，我还要
骂观众。坚持不懈的尖叫，这是*我的*电影，没有人会再看到它，我将撕裂一半屏幕，电影放映机
将在破烂的卷轴中旋转。而且那就是电影的结尾。人们将*非常*愤怒。

现在，我得思考。你看，实际上，Alec Baldwin在*特南鲍姆一家*中做一个体面的旁白。
他的职业生涯可能是正确的。你可能不想用他，他可能也不想做这个。

告诉你。我要做好这个角色。我已经走出了职业生涯的最低点。
{% endcapture %}
{{ sidebar | markdownify }}
</aside></div>

<a name="section2"></a>

## 2. 词性

就像臭鼬背部的白色条纹，新娘飘动的白裙一样，ruby的很多词性都有特别的视觉提示，以帮助你
识别它们。标点符号和大小写将帮助你的大脑很好的辨别看到的代码。你会在心里大喊*嘿，我认识这家伙！*
你也可以在与其他Ruby爱好者谈话中这样来提高自己的身份。

尝试着关注每个词性的长相。下面本书将详细的介绍这些特性。我给每个词性都归纳了一些简短的描述，
你不需要理解那些解释。在这章的结尾，你应该能够认识Ruby语言的每个词性。

### 变量

在ruby中每个普通的小写单词都是一个变量。变量可能由字母、数字和下划线组成。

例如：`x`, `y`, `banana2` 或者 `phone_a_quail` 。

变量就好比一个昵称。还记得过去人们都叫你臭Pete吗？人们可能说，“走开，臭Pete!”
并且所有人都奇迹般的知道臭Pete就是你。

变量，就是你给频繁用到的东西取个昵称。比如，我们假设你开了一个孤儿院。这是一个吝啬的孤儿院。
每当Warbucks爸爸过来领养孩子时，我们坚持让他付给我们**一百二十一美元八美分**来购买孩子的泰迪熊，
那是孩子在黑夜中和在这噩梦般环境中的唯一依赖。


{% highlight rb %}
teddy_bear_fee = 121.08
{% endhighlight %}

后来，让你让他在收银机（一个运行ruby程序的强大马力的收银机）上按下按钮时，
你需要将所有的费用加起来作为**总额**。

{% highlight rb %}
total = orphan_fee + teddy_bear_fee + gratuity
{% endhighlight %}

那些变量的昵称当然有帮助。而在破旧的地下销售儿童过程中，我保证任何帮助都将获得赞赏。

![They mock my examples.](../images/the.foxes-4a.png "They mock my examples.")

### 数字

数字中最基本类型就是*integer*了，以**加号或减号**开头的**一连串的数字**。

例如：`1`, `23`, 和 `-10000`。

逗号是不允许出现在数字中的，但是可以用下划线代替。所以如果你觉得需要在数字中用千位分开，
那就使用下划线吧。

{% highlight rb %}
population = 12_000_000_000
{% endhighlight %}

在Ruby中浮点数叫做*floats*。浮点数包含**小数点**或者使用**科学计数法**。

例如：`3.14`, `-808.08` 和 `12.043e-04` 。

### 字符串

字符串是使用引号包起来的任意多个字符（字母，数字，标点符号）的组合。**单引号和双引号**
都可以用来创建字符串。

例如：`"sealab"`, `'2021'`, 或者 `"These cartoons are hilarious!"` 。

当你把字符放到引号中，他们被一起保存成一个单独的字符串。

想想一个记者粗略的记录一个名人的闲谈。”我是多么的聪明，“Avril Lavigne说道。
”现在我知道商业是什么了——你必须要做哪些事并且怎么去做。“

{% highlight rb %}
avril_quote = "I'm a lot wiser.  Now I know
what the business is like -- what you have
to do and how to work it."
{% endhighlight %}

所以，就像我们保存一个数字在变量**teddy_bear_fee**中一样，现在我们正在保存一个
字符集合（字符串）到变量**avril_quote**中。那个记者把这段引用输入打印机，他碰巧
使用Ruby来处理打印操作。

{% highlight rb %}
print oprah_quote
print avril_quote
print ashlee_simpson_debacle
{% endhighlight %}

![They desire to be in my examples.](../images/the.foxes-4b.png "They desire to
be in my examples.")

### 名字

名字就和变量看起来差不多。同样，他们也是由字母，数字或者下划线组成。但是，他们是
由**由冒号开头**。

例如：`:a`, `:b`, 或者 `:ponce_de_leon` 。

名字是轻量级的字符串。通常，symbols使用在你需要一个字符串但是不会把它打印在屏幕的情况下。

你可以说一个名字可以更简单的在电脑中使用。它就像一个抗酸剂。那个冒号表示气泡在你计算机的肠胃中
缓缓上浮就像它消化了symbol一样。啊，甜美，甜美的救济。

![Chunky bacon!!](../images/the.foxes-4c.png "Chunky bacon!!")

### 常量

常量的单词就像变量一样，但是常量是**大写的**。如果变量是Ruby的名词，那么把变量想象成专有名词。

例如：`Time`, `Array` or `Bunny_Lake_is_Missing` 。

在英语中，专有名词是大写的。The Empire State Building（帝国大厦）。你不能移走帝国大厦。
你甚至不能把帝国大厦想象成其他事物。专有名字就像那样。他们指代那些非常特别并且通常不会因为时间改变的事物。

同样的道理，常量在赋值之后也不能被改变。

{% highlight rb %}
EmpireStateBuilding = "350 5th Avenue, NYC, NY"
{% endhighlight %}

如果我们试图改变常量，Ruby会抱怨我们。这样的事情是不推荐的。

![Come on, chunky bacon.](../images/the.foxes-4d.png "Come on, chunky bacon.")

### 方法

如果把变量和常量比作名词，那么方法可以比作动词。方法通常是在变量或者常量的后面并且通过一个**点**
连接。你已经看到方法在工作了。

{% highlight rb %}
front_door.open
{% endhighlight %}

上面的代码中，**open**就是方法。它是一个行为，是个动词。在一些情况在，你将看到一些行为连接在一起。

{% highlight rb %}
front_door.open.close
{% endhighlight %}

我们已经指示电脑把前门打开，然后再立刻把门关上。

{% highlight rb %}
front_door.is_open?
{% endhighlight %}

上面也是一个行为。我们正在指示电脑去检查门是否敞开的。这个方法可以这样写
`Door.test_to_see_if_its_open`,但是`is_open?`更加简明而且也是正确的。感叹号和
问号也可能出现在方法名中。

### 方法参数

一个方法可能需要更多的信息去执行它的行为。如果我们想要电脑去给门喷漆，我们应该提供颜色。

方法参数在方法名的末尾。参数经常被**括号**包围，并且被**逗号**分开。

{% highlight rb %}
front_door.paint( 3, :red )
{% endhighlight %}

上面的代码给前门涂上了3个红色的外套。

你可以把这想象成方法正在沿着内轮胎边缘拉动，包括他的额外指令。括号是带着内管的湿气。
那些逗号是每个参数的脚，贴在边缘。最后一个参数把它的脚盘着在，我们就不展示了。

带着方法的参数连接在一起，就像一艘船拉着许多内胎。

{% highlight rb %}
front_door.paint( 3, :red ).dry( 30 ).close()
{% endhighlight %}

上面的代码把前门涂上3件红色的外套，烘干20分钟，然后关上门。即使最后一个方法没有参数，
如果你愿意的话也可以加上括号。拖着一个空的内胎也没有什么意义，所以那个括号通常都省略掉。

有些方法（例如`print`）是核心方法。这些方法是在Ruby中自始至终都会用到。以为他们太常见，
你可以不适用点来引用。

{% highlight rb %}
print "See, no dot."
{% endhighlight %}

### 类方法

就如上面描述的方法（也叫*实例*方法）一样，类方法也是经常在变量和常量后面。
这里不是使用点，而是使用**双冒号**来引用。

{% highlight rb %}
Door::new( :oak )
{% endhighlight %}

如上面看到的，这个`new`类方法经常用来创建事物。在上面的例子中，我们正在请求Ruby
来为我们创建一个新的橡木门。当然，Ruby必须能够理解怎样制造一个门——也是就大量的木材，
伐木工人和那些长长的扭动的二人锯片。

![Plenty of chunky bacon to go around.](../images/the.foxes-4e.png "Plenty of
chunky bacon to go around.")

### 全局变量

那些以**美元符号**开头的变量是全局的。

例如：`$x`, `$1`, `$chunky` 和 `$CHunKY_bACOn` 。

大部分变量本质上都是临时的。你程序的某些部分就像是一个小房子，你走进去看到他们有自己的变量。
在一个房间里，你可能有一个`dad`代表着Archie,一个旅行推销员和一个古玩收藏家。
在另一个房间，`dad`可以代表Peter,一个爱穿法兰绒的训狮者。每个房间都有对于`dad`自己的意思。

使用全局变量，你能够保证这个变量在每个小房间里都代表相同的意思。美元符号是非常合适的。
每个美国家庭都认同美元的价值。我们为之疯狂的东西。在美国，试着敲任何一扇门，然后给他们现金。
我敢保证，如果你敲门并给他们热爱法兰绒的驯兽师Peter，肯定不会得到相同的反应。

全局变量可以用在程序的任何地方。他们永远不会淡出人们的视野。

### 实例变量

那些以**@**标识符开头的变量称为实例变量。

例如：`@x`, `@y`, 和 `@only_the_chunkiest_cut_of_bacon_I_have_ever_seen` 。

这些变量经常用来定义事物的属性。例如，你可能通过设置`front_door`里面的变量`@width`值来给Ruby
提供`front_door`的宽度。在Ruby中，实例变量被用来定义单一对象的特性。

把**@(at)**标识符想象成**属性(attribute)**

### 类变量

那些以**两个at(@@)**开头的变量称为类变量。

例如`@@x`, `@@y`, 和 `@@i_will_take_your_chunky_bacon_and_raise_you_two` 。

类变量，也是用来定义属性的。但在Ruby中不是定义一个单一对象的属性，而是定义多个对象
的关联属性。如果实例变量是用来设置了单一对象`front_door`的属性，那么类变量用来设置`Door`
的每个属性。

把**@@**想象成**所有属性(attribute all)**的前缀。此外，你可以从*星球大战*中想象
一大群**AT-ATs**，全部听从Ruby的命令。你改变一个类变量并不是改变一个，他们所有的
都会改变。

![Woohoo! Chunky bacon accomplished!](../images/the.foxes-4f.png "Woohoo! Chunky
bacon accomplished!")

### 程序块

每段被**花括号**包围的代码都是一个程序块。

{% highlight rb %}
2.times {
  print "Yes, I've used chunky bacon in my examples, but never again!"
}
{% endhighlight %}

使用程序块，你能够把一些指令集合到一起，然后他们可以在程序中传递。花括号就好像
螃蟹的两个钳子抢走了代码并把他们围在了一起。当你看到这两个钳子，记住里面的代码
已经被压成一个单元。

它就像那些小小的Hello Kitty盒子一样，里面装满了小铅笔盒小橡皮放在购物广场上出售，
它们所有的都使用透明的闪烁的包装，好让它们可以放在手上以隐蔽它们的文具属性。
除了程序块不要求眯着要看其他地方都是一个道理。

花括号也可以使用单词**do**和**end**代替，当你的程序块多余一行时这将很好。

{% highlight rb %}
loop do
  print "Much better."
  print "Ah.  More space!"
  print "My back was killin' me in those crab pincers."
end
{% endhighlight %}

### 参数块

参数块是被**管状符**包围并用**逗号**分割的一组变量。

例如：`|x|`, `|x,y|`, 和 `|up, down, all_around|` 。

参数块被用再一个程序块的开头。

{% highlight rb %}
{ |x,y| x + y }
{% endhighlight %}

在上面的例子中，`|x,y|`是参数。在参数后面，我们有一些代码。表达式`x + y`将两个参数加起来。

我喜欢将管状符比作一个隧道。他们就像一个斜槽，而变量顺着滑下。（正当`y`经过她的大腿时，
`x`以鹰速下降）这个斜槽充当着程序块和它周围事物的一个通道。

变量通过这个斜槽（或者隧道）传入程序块中。

![And then, the dismal truth.](../images/the.foxes-4g.png "And then, the dismal
truth.")

### 连续范围

范围是使用**圆括号**包围并使用**省略号**（以两个或者三个点的形式）分开的两个变量。

* `(1..3)` 是一个范围, 表示从1到3之间的数字。
* `('a'..'z')` 是一个范围，表示小写字母表。

把这想象成一个已经被挤倒便于携带的手风琴。（当然，你可以通过携带一个展开的手风琴来获得巨大的个人价值，
但是有时候人们需要沉湎于自我怀疑中将手风琴小心的挤压在一起。）圆括号就是小型手持手风琴两侧的手柄。
中间的点就是链，保持手风琴紧紧地折叠在一起。

Normally, only two dots are used. If a third dot is used, the last value in the
range is excluded.
通常，只有两个点被使用。如果第三个点被使用了，该范围的最后一个值会被排除。

* `(0...5)` 表示数字0至4。

When you see that third dot, imagine opening the accordion slightly. Just enough
to let one note from its chamber. The note is that end value. We’ll let the sky
eat it.
当你看到了第三个点，想象轻微打开的手风琴。只是足够让一个音符从它的室内露出。那个音符就是
那最后的值。我们让天空吃了溢出的最后的值。

### 数组

数组是由**方括号**包围并被**逗号**分割的一个列表。

* `[1, 2, 3]` 是一个数字数组。
* `['coat', 'mittens', 'snowboard']` 是一个字符串数组。

Think of it as a caterpillar which has been stapled into your code. The two
square brackets are staples which keep the caterpillar from moving, so you can
keep track of which end is the head and which is the tail. The commas are the
caterpillar’s legs, wiggling between each section of its body.

Once there was a caterpillar who had commas for legs. Which meant he had to
allow a literary pause after each step. The other caterpillars really respected
him for it and he came to have quite a commanding presence. Oh, and talk about a
philanthropist! He was notorious for giving fresh leaves to those
less-fortunate.

Yes, an array is a collection of things, but it also keeps those things in a
specific order.

### Hashes

A hash is a dictionary surrounded by **curly braces**. Dictionaries match words
with their definitions. Ruby does so with **arrows** made from an equals sign,
followed by a greater-than sign.

`{'a' => 'aardvark', 'b' => 'badger'}` is an example.

This time, the curly braces represent little book symbols. See how they look
like little, open books with creases down the middle? They represent opening and
closing our dictionary.

Imagine our dictionary has a definition on each of its pages. The commas
represent the corner of each page, which we turn to see the next definition. And
on each page: a word followed by an arrow pointing to the definition.

{% highlight rb %}
{ 'name' => 'Peter', 'profession' => 'lion tamer', 'great love' => 'flannel' }
{% endhighlight %}

I’m not comparing hashes to dictionaries because you can only store definitions
in a hash. In the example above, I stored personal information for Peter, the
lion tamer with a great love for flannel. Hashes are like dictionaries because
they can be very easy to search through.

![The foxes think silence will kill the comic.](../images/the.foxes-5.png "The
foxes think silence will kill the comic.")

### Regular Expressions

A regular expression (or _regexp_) is a set of characters surrounded by
**slashes**.

`/ruby/`, `/[0-9]+/` and `/^\d{3}-\d{3}-\d{4}/` are examples.

Regular expressions are used to find words or patterns in text. The slashes on
each side of the expression are pins.

Imagine if you had a little word with pins on both side and you held it over a
book. You pass the word over the book and when it gets near a matching word, it
starts blinking. You pin the regular expression onto the book, right over the
match and it glows with the letters of the matching word.

Oh, and when you poke the pins into the book, the paper sneezes, _reg-exp!_

Regular expressions are much faster than passing your hand over pages of a book.
Ruby can use a regular expression to search volumes of books very quickly.

### Operators

You’ll use the following list of operators to do math in Ruby or to compare
things. Scan over the list, recognize a few. You know, addition `+` and
subtraction `-` and so on.

    ** !  ~  *  /  %  +  -  &
    << >> |  ^  >  >= <  <= <=>
    || != =~ !~ && += -= == ===
    .. ... not and or

### Keywords

Ruby has a number of built-in words, imbued with meaning. These words cannot be
used as variables or changed to suit your purposes. Some of these we’ve already
discussed. They are in the safe house, my friend. You touch these and you’ll be
served an official syntax error.

    alias   and     BEGIN   begin   break   case    class   def     defined
    do      else    elsif   END     end     ensure  false   for     if
    in      module  next    nil     not     or      redo    rescue  retry
    return  self    super   then    true    undef   unless  until   when
    while   yield

Good enough. These are the illustrious members of the Ruby language. We’ll be
having quite the junket for the next three chapters, gluing these parts together
into sly bits of (poignant) code.

I’d recommend skimming all of the parts of speech once again. Give yourself a
broad view of them. I’ll be testing your metal in the next section.

![Out in the pickup truck.](../images/the.foxes-6.png "Out in the pickup
truck.")

<div class=sidebar><aside>
{% capture sidebar %}
## Seven Moments of Zen from My Life

1. 8 years old. Just laying in bed, thinking. And I realize. _There’s nothing
stopping me from becoming a child dentist._
2. 21\. Found a pencil on the beach. Embossed on it: _I cherish serenity._ Tucked
it away into the inside breast pocket of my suit jacket. Watched the waves come
and recede.
3. 22\. Found a beetle in my bathroom that was just about to fall into a heating
vent. Swiped him up. Tailored him a little backpack out of a leaf and a thread.
In the backpack: a skittle and a <span class="caps">AAA</span> battery. That
should last him. Set him loose out by the front gate.
4. Three years of age. Brushed aside the curtain. Sunlight.
5. 14\. Riding my bike out on the pier with my coach who is jogging behind me as
the sun goes down right after I knocked out Piston Honda in the original
Nintendo version of Mike Tyson’s Punch-Out.
6. 11\. Sick. Watching Heathcliff on television. For hours, it was Heathcliff.
And he was able to come right up close to my face. His head spun toward me. His
face pulsed back and forth, up close, then off millions of miles away. Sound was
gone. In fractions of a second, Heathcliff filled the universe, then blipped off
to the end of infinity. I heard my mother’s voice trying to cut through the
cartoon. Heathclose, Heathaway, Heathclose, Heathaway. It was a religious rave
with a cat strobe and muffled bass of mother’s voice. (I ran a fever of 105 that
day.)
7. 18\. Bought myself a gigapet. A duck. Fed it for awhile. Gave it a bath.
Forgot about it for almost a couple months. One day, while cleaning, I found a
chain and he was there on the end. Hey, little duck. Mad freaky, hoppin’ around
with his hair out, squawking diagonal lines. In a tuxedo.
{% endcapture %}
{{ sidebar | markdownify }}
</aside></div>

<a name="section3"></a>

## 3. If I Haven't Treated You Like a Child Enough Already

I’m proud of you. Anyone will tell you how much I brag about you. How I go on
and on about this great anonymous person out there who scrolls and reads and
scrolls and reads. “These kids,” I tell them. “Man, these kids got heart. I
never…” And I can’t even finish a sentence because I’m absolutely blubbering.

And my heart glows bright red under my filmy, translucent skin and they have to
administer 10cc of JavaScript to get me to come back. (I respond well to toxins
in the blood.) Man, that stuff will kick the peaches right out your gills!

So, yes. You’ve kept up nicely. But now I must begin to be a brutal
schoolmaster. I need to start seeing good marks from you. So far, you’ve done
nothing but move your eyes around a lot. Okay, sure, you did some exceptional
reading aloud earlier. Now we need some comprehension skills here, Smotchkkiss.

**Say aloud each of the parts of speech used below.**

{% highlight rb %}
5.times { print "Odelay!" }
{% endhighlight %}

You might want to even cover this paragraph up while you read, because your eyes
might want to sneak to the answer. We have a _number_ `5`, followed by a
_method_ `.times`. Then, the first crab pincers of a _block_. The kernel
_method_ `print` has no dot and is followed by a _string_ `"Odelay!"`. The final
crab pincers close our _block_.

**Say aloud each of the parts of speech used below.**

{% highlight rb %}
exit unless "restaurant".include? "aura"
{% endhighlight %}

Like the `print` method, `exit` is a kernel _method_. If you were paying
attention during the big list of keywords, you’ll know that `unless` is just
such a _keyword_. The _string_ `"restaurant"` is clung to by the _method_
`include?`. And finally, the string `"aura"`.

**Say aloud each of the parts of speech used below.**

{% highlight rb %}
['toast', 'cheese', 'wine'].each { |food| print( food.capitalize ) }
{% endhighlight %}

This caterpillar partakes of finer delicacies. An _array_ starts this example.
In the array, three _strings_ `'toast'`, `'cheese'`, and `'wine'`. The whole
array is trailed by a _method_ `each`.

Inside of a _block_, the _block argument_ `food`, traveling down its little
waterslide into the block. The _method_ `capitalize` then capitalizes the first
letter of the block argument, which has become _variable_ `food`. This
capitalized _string_ is passed to kernel _method_ `print`.

Look over these examples once again. Be sure you recognize the parts of speech
used. They each have a distinct look, don’t they? Take a deep breath, press
firmly on your temples. Now, let’s dissect a cow’s eye worth of code.

<a name="section4"></a>

## 4. An Example to Help You Grow Up

![Gettin' cabin fever.](../images/the.foxes-7.png "Gettin' cabin fever.")

**Say aloud each of the parts of speech used below.**

{% highlight rb %}
require 'net/http'
Net::HTTP.start( 'www.ruby-lang.org', 80 ) do |http|
  print( http.get( '/en/about/license.txt' ).body )
end
{% endhighlight %}

The first line is a method call. The _method_ called `require` is used. A
_string_ is passed to the method containing `'net/http'`. Think of this first
line of code as a sentence. We have told Ruby to load some helper code, the
`Net::HTTP` library.

The next three lines all go together. The _constant_ `Net::HTTP` refers to the
library we loaded above. We are using the _method_ `start` from the library.
Into the method, we’re sending a _string_ `'www.ruby-lang.org'` and the _number_
`80`.

The word `do` opens a _block_. The block has one _block variable_ `http`. Inside
the block, the _method_ `print` is called. What is being printed?

From the _variable_ `http`, the _method_ `get` is called. Into `get`, we pass a
_string_ containing the path `'/en/about/license.txt'`. Now, notice that another
method is chained onto `get`. The _method_ `body`. Then, the block closes with
`end`.

Doing okay? Just out of curiosity, can you guess what this example does?
Hopefully, you’re seeing some patterns in Ruby. If not, just shake your head
vigorously while you’ve got these examples in your mind. The code should break
apart into manageable pieces.

For example, this pattern is used a number of times:

    _variable_ . _method_ ( _method arguments_ )

You see it inside the block:

{% highlight rb %}
http.get( '/en/about/license.txt' )
{% endhighlight %}

We’re using Ruby to get a web page. You’ve probably used <span
class="caps">HTTP</span> with your web browser. <span class="caps">HTTP</span>
is the Hypertext Transfer Protocol. <span class="caps">HTTP</span> is used to
transfer web pages across the Internet. Conceptualize a bus driver that can
drive across the Internet and bring back web pages for us. On his hat are
stitched the letters <span class="caps">HTTP</span>.

The variable `http` is that bus driver. The _method_ is a message to the bus
driver. Go `get` the web page called `/en/about/license.txt`.

So where you see the chain of methods:

{% highlight rb %}
http.get( '/en/about/license.txt' ).body
{% endhighlight %}

Since we’ll be getting back a web page from the `http` bus driver, you can read
this in your brain as:

    _web page_ .body

And this bit of code:

{% highlight rb %}
print( http.get( '/en/about/license.txt' ).body )
{% endhighlight %}

This code gets the web page. We send a `body` message to the web page, which
gives us all the <span class="caps">HTML</span> in a _string_. We then `print`
that string. See how the basic dot-method pattern happens in a chain. The next
chapter will explore all these sorts of patterns in Ruby. It’ll be good fun.

So, what does this code do? It prints the <span class="caps">HTML</span> for the
Ruby home page to the screen using an web-enabled bus driver.

<a name="section5"></a>

## 5. And So, The Quick Trip Came To An Eased, Cushioned Halt

![Running after the truck.](../images/the.foxes-8.png "Running after the
truck.")

So now we have a problem. I get the feeling that you are enjoying this way too
much. And you haven’t even hit the chapter where I use jump-roping songs to help
you learn how to parse <span class="caps">XML</span>!

If you’re already enjoying this, then things are really going bad. Two chapters
from now you’ll be writing your own Ruby programs. In fact, it’s right about
there that I’ll have you start writing your own role-playing game, your own
file-sharing network (a la BitTorrent), as well as a program that will pull
genuine random numbers from the Internet.

<p style="float:right">
  <img src="../images/graph-1.gif"
    title="Proof has been extracted from the pudding."
    alt="Proof has been extracted from the pudding.">
</p>

And you know (you’ve got to know!) that this is going to turn into an obsession.
First, you’ll completely forget to take the dog out. It’ll be standing by the
screen door, darting its head about, as your eyes devour the code, as your
fingers slip messages to the computer.

Thanks to your neglect, things will start to break. Your mounds of printed
sheets of code will cover up your air vents. Your furnace will choke. The trash
will pile-up: take-out boxes you hurriedly ordered in, junk mail you couldn’t
care to dispose of. Your own uncleanliness will pollute the air. Moss will
infest the rafters, the water will clog, animals will let themselves in, trees
will come up through the foundations.

But your computer will be well-cared for. And you, Smotchkkiss, will have
nourished it with your knowledge. In the eons you will have spent with your
machine, you will have become part-CPU. And it will have become part-flesh. Your
arms will flow directly into its ports. Your eyes will accept the video directly
from <span class="caps">DVI</span>-24 pin. Your lungs will sit just above the
processor, cooling it.

And just as the room is ready to force itself shut upon you, just as all the
overgrowth swallows you and your machine, you will finish your script. You and
the machine together will run this latest Ruby script, the product of your
obsession. And the script will fire up chainsaws to trim the trees, hearths to
warm and regulate the house. Builder nanites will rush from your script,
reconstructing your quarters, retiling, renovating, chroming, polishing,
disinfecting. Mighty androids will force your crumbling house into firm, rigid
architecture. Great pillars will rise, statues chiseled. You will have dominion
over this palatial estate and over the encompassing mountains and islands of
your stronghold.

So I guess you’re going to be okay. Whatdya say? Let’s get moving on this script
of yours?


  [1]: http://www.whiskeyclone.net/ghost/L/lordonlyknows.html
