---
title: "你好,Ruby"
permalink: book/chapter-2.html
layout: chapter
sections:
- - section1
  - 开篇
- - section2
  - 小狗的故事
- - section3
  - 红日升
- - section4
  - 书的开头
---

<a name="section1"></a>

## 1. 开篇

假设你已经打开了这本书（其实你已经打开了），首先映入眼帘的是一个大洋葱，它就在书的中央。
（在我的要求下，本书的出版商赠送洋葱一个。）

你可能会惊讶，“哇，这本书还带了一个洋葱”（即使你可能不喜欢洋葱，我保证你会对在一本编程手册中附赠蔬菜感兴趣。）

然后你会问自己，“等下，这本书不是讲ruby——那来自日本的神奇语言的吗？而且即使我对在编程手册
中附赠蔬菜确实感兴趣，但为什么是洋葱？我要拿它做什么呢？”

不。先别纠结这个。你不用对洋葱怎么样，把它放一边，等它来找你。

我们开诚布公好了。我要你哭。我要你流泪。我要你泪流满面。这是本**辛酸的**Ruby指南书。也就是说，里面的代码如此美妙，你的眼泪不得不决堤；
也就是说，你一觉醒来一定是抱着这本书，舍不得放手！必要的话也可以定做个*_Why先生（心酸的）Ruby指南_*的专用豪华皮套，这样你和这本书就可以形影不离了！

你确实需要抽泣一次，至少也要掉泪。要是还没有反应，洋葱会让这一切发生。

<div class=sidebar><aside>
{% capture sidebar %}
## 我要怎样处理这本书带来的巨大收益

任何一个写书的人会告诉你一个作者会多么容易的被自己宏伟的幻觉所分心。以我的经验来看，每个段落我会停止2次，每个连环画的板面会停止4次，只是为了预想这本书将来会给我的生活带来巨大的财富和繁荣。在我的头脑里也总是燃烧着这样的想法，我害怕写这本书会让我在向无敌越野车和豪华加长轿车的道路上止步不前。

然而这没有阻止我创作这本（辛酸的）指南，我保留这个空间作为我空想徒劳愿望的一个安全区域。

今天我在这所格拉纳多的意式餐馆，当我正在付款的时候，碰巧注意到了（玻璃下的）一瓶香醋的售价是150美元。相当的便宜。我可以把它藏在手掌下，22岁。

我花了太多的时间在想着那瓶香醋上。通常这在我的那些强迫性幻想中只算是小菜一碟。在一次幻想中，我走进一家餐馆，扔一堆绿叶到柜台并认真的对收银员说，“快点！我还有一个重要的色拉要做！”

在另一个相关的幻想中，我正在扔掉食物。这些粗粮根本配不上我的新醋。不，我必须得指出名声和富裕的生活已经腐败到了我的内心。我新的食物将是金钱。高贵冷艳的现金小姐。

等会，我将要花费几百美元买一个块myzithra奶酪。

不过，我的想象早已超出了我的财富。我想象我已经收购了希腊古瓮，汽车公司，航空公司，金字塔，恐龙化石等等。偶然间我在新闻里面看到城市遭到暴风袭击，于是我就在我的购物清单上写下了：*飓风*。

但是现在我有一个更宏伟的目标。简而言之：如果我积累的如此多的财富以至于印钞厂都不能生产足够的纸币已跟上我的需求，怎么样？因此，其他所有人都被迫使用垄断的纸币作为实际通货。那样你就必须要挣得垄断的纸币来保持桌子上的食物。这将是场严肃而紧张的游戏。我的意识是你必须抵押你的房子然后你的孩子将要哭泣。
因此，我认为你将要成为那些选择地下停车场作为城市资金，就像[地下国库](http://groups.yahoo.com/group/monopoly/message/37)中描述的那样。

但是，你需要借助有趣的钱。假钱规则。你很快就能得到很多钱。一时间，看起来你成为了一个大富翁。
小时候，我聚集了一些邻居的孩子，在我们的街道上建立了这个小的蒂华纳城。我们制定了自己的比索(一种货币)，穿阔边帽和所有的事情。

一个小孩正在以2比索每个的价格卖热玉米粉蒸肉。*2个比索*！这个孩子知道这些钱是假的吗？
还是他疯了？谁邀请的这个小孩？他难道不知道这不是真的蒂华纳城？也许他真的是来自蒂华纳城！
也许这些事*真实的*比索！让我们去赚更多*真实的*比索！

我认为，我们甚至有一个小酒馆，你可以在那里喝个酩酊大醉。再没有像一群小孩在那里跌跌撞撞，使用幼嫩的嘴唇喃喃自语语无伦次的场景了。
{% endcapture %}
{{ sidebar | markdownify }}
</aside></div>

<a name="section2"></a>

## 2. 小狗的故事

先看下这个辛不辛酸：

一天，我在一条满是汽车卖场的大街上（当时就是我的婚事取消不久）发现了一只黑毛流浪狗，
它的眼睛绿里透红。我觉得同病相怜，就从卖场的一根柱子那里取下两个气球绑到了它项圈上。
我就认为它是我的狗了，就叫它Bigelow。

买狗粮去，买完狗粮就回我住处，到时候我们可以随便躺在椅子上听听Gorky的Zygotic Mynci。
哦，对了，还得找家店给Bigelow买个躺椅。

不过Bigelow可没认我当主人。五分钟一过，这混蛋小狗就跟我分道扬镳了，我还追不上。
可怜的小狗走丢了第二次，狗粮和躺椅都成了昨日梦幻。小狗只跟了我五分钟。

该死的反骨仔。我就坐在街边的椅子上朝三羊过桥的雕像扔松果，随着哭了个把小时，眼泪不争气啊。
好吧，你现在该觉得有点辛酸了。

我想，它会把那气球带到哪？那只疯狗看着一定跟个长腿儿的气球似的。

不多久我就牵上了新的Bigelow一打印了一堆的Ruby读物，都是网上的文章。后来我在回家的火车上扫过一遍，
只看了五分钟，毫无深刻可言。

我就坐着看窗外的世界，任这纷繁万千在眼前融化。*小语言啊，这世界太大了。*，我想。
*你小东西什么也轮不着，没你站立的脚，也没你游泳的手。*

这就是当时的我，小破火车里的小人儿（甚至还有颗乳牙还没掉）。这个蓝色星球上住着几十亿人，
又怎轮着我装上宝石(Ruby)运？谁又拿得准我第二天会不会被手机噎死？Why先生已死，Ruby永存。

墓志铭就这么写：

> 他的气管里有啥？瞧啊，一只诺基亚！

万幸万幸，我终于可以在地下边睡个安稳觉了一只不过铃音会不定期的来囧我。

<a name="section3"></a>

## 3. The Red Sun Rises

So, now you’re wondering why I changed my mind about Ruby. The quick answer is:
we clicked.

Like when you meet Somebody in college and they look like somebody who used to
hit you in the face with paintbrushes when you were a kid. And so, impulsively,
you conclude that this new Somebody is likely a non-friend. You wince at their
hair. You hang up phones loudly during crucial moments in their anecdotes. You
use your pogo stick right there where they are trying to walk!

Six months later, somehow, you and Somebody are sitting at a fountain having a
perfectly good chat. Their face doesn’t look so much like that childhood
nemesis. You’ve met the Good Twin. You clicked.

So whereas I should probably be pounding your teeth in with hype about Ruby and
the tightly-knit cadre of pertinent acronyms that accompany it everywhere
(whetting the collective whistles of your bosses and their bosses’ bosses),
instead I will just let you coast. I’ll let you free-fall through some code,
interjecting occasionally with my own heartfelt experiences. It’ll be quite
easy, quite natural.

I should offer you some sort of motivation, though. So, Smotchkkiss, I’m going
to give my three best reasons to learn Ruby and be done with it.

1.  **Brain health.**
    
    Vitamin R. Goes straight to the head. Ruby will teach you to _express_ your
ideas through a computer. You will be writing stories for a machine.
    
    Creative skills, people. Deduction. Reason. Nodding intelligently. The
language will become a tool for you to better connect your mind to the world.
I’ve noticed that many experienced users of Ruby seem to be clear thinkers and
objective. (In contrast to: heavily biased and coarse.)

2.  **One man on one island.**
    
    Ruby was born in Japan. Which is freaky. Japan is not known for its
software. And since programming languages are largely written in English, who
would suspect a language to come from Japan?
    
    And yet, here we have Ruby. Against the odds, Yukihiro Matsumoto created
Ruby on February 24, 1993. For the past ten years, he has steadily brought Ruby
to a global audience. It’s triumphant and noble and all that. Support diversity.
Help us tilt the earth just a bit.

3.  **Free.**
    
    Using Ruby costs nothing. The code to Ruby itself is open for all of the
world to inhale/exhale. Heck, this book is free. It’s all part of a great, big
giveaway that should have some big hitch to it.
    
    You’d think we’d make you buy vacuums or timeshare or fake Monets. You’d
think there’d be a 90 minute presentation where the owner of the company comes
out at the end and knuckles you into sealing the deal.
    
    Nope, free.

With that, it’s time for the book to begin. You can now get out your highlighter
and start dragging it along each captivating word from this sentence on. I think
I have enough hairspray and funny money on my person to keep me sustained until
the final page.

<a name="section4"></a>

## 4. How Books Start

Now, if you ever have read a book, you know that no book can properly start
without an exorbitant amount of synergy. Yes, synergy. Maybe you didn’t know
this. Synergy means that you and I are supposed to cooperate to make this a
great reading experience.

We start off the book by getting along well in the Introduction. This
togetherness, this **synergy**, propels us through the book, with me guiding you
on your way. You give me a reassuring nod or snicker to indicate your progress.

I’m Peter Pan holding your hand. Come on, Wendy! Second star to the right and on
till morning.

One problem here. I don’t get along well with people. I don’t hold hands very
well.

Any of my staff will tell you. At the Opening Ceremonies of This Book (a catered
event with stadium seating), I discovered that the cucumber sandwiches weren’t
served in tea towels. As a result, the butter hadn’t set with the cucumbers
right… Anyways, I made a big scene and set fire to some of the advertising
trucks outside. I smashed this spotlight to pieces and so on. I had this loud
maniacal laughing thing going on deep into that night. It was a real mess.

But, since I don’t get along well with people, I hadn’t invited anyone but
myself to the Opening Ceremonies of This Book. So it wasn’t really that
embarrassing. I kept it under wraps and no one found out about the whole ordeal.

So you’ve got to know that **synergy** doesn’t actually mean **synergy** in this
book. I can’t do normal **synergy**. No, in this book, **synergy** means
**cartoon foxes**. What I’m saying is: this book will be starting off with an
exorbitant amount of **cartoon foxes**.

And I will be counting on you to turn them into **synergy**.
