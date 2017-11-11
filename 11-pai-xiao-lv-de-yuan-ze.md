
# 1.1 牌效率的原则

本章讲述的是对于牌效率需要知道的原则。

这里的牌效率是指在他家没有明确的进攻的情况下，以最大化每一局的收支期待值为目标的打牌技术。(如何应对他家的进攻的技术是攻防判断。面对他家进攻时选择打牌的技术有限制他家、兜牌和弃和。)

## 选择和率最大化

每一局的收支期待值可以用 <code>(和率)x(打点)+(没有和牌时的收支 ※除了流局听牌以外这个收支都是负的)</code> 来表示。

因此，除了为了提升打点或者减少没有和牌时的支出以外的情况下，都应当以最大化和率为目标打牌。（可以为了提高打点，增加高打点的进张而降低整体的进张。但是只是因为不想和低打点的牌而降低整体的进张，强行留着手牌中和其他牌相比比较差的牌是不可取的。）

例：
<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/3m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/7p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/7p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/8p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/8s.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/9s.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/5z.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/5z.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/6z.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/7z.gif' height='32px'>

期待役牌成对和筒子的进张不切字牌选择打<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/8s.gif' height='24px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/9s.gif' height='24px'>是可以的（平场的序盘应该这样打），但是因为<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2m.gif' height='24px'>・<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/5m.gif' height='24px'>进张之后会降低打点，强行拆<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/3m.gif' height='24px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4m.gif' height='24px'>是不可取的。

## 保留选择的余地基本没有好处（读不懂，暂时跳过）

## 关于有效牌的思考方式
在选择切牌A还是牌B的时候，要对这两张牌的有效牌进行考察。某张牌的有效牌是指，当摸到这张有效牌的时候，会选择切出"某张牌"以外的牌。因此，就算一眼看上去是"某张牌"的有效牌的牌，如果摸到这张牌的时候还是会把"某张牌"切掉的话，就不能算作有效牌了。

例:对于单独的<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/1p.gif' height='24px'>来说虽然<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2p.gif' height='24px'>、<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/3p.gif' height='24px'>在大多数情况下是有效牌，但是如果已经存在4个以上更好的block（比如面子或者两面搭子）的话即使摸到<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2p.gif' height='24px'>、<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/3p.gif' height='24px'>最终也会打掉，所以这里的<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2p.gif' height='24px'>、<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/3p.gif' height='24px'>不能算做有效牌。

有效牌有很多种类。（例如有的可以形成搭子，有的可以形成面子，有的可以让搭子变成更好的搭子，等等。）相同种类的有效牌可以只看这一部分来比较，但是对于不同种类的有效牌很难一对一的直接比较（比较不同种类的有效牌的时候需要其他的方法）。

但是，上面的有效牌里可以明确的区分出降低向听的和不降低向听的两种，原则上应当优先选择降低向听的有效牌比较好的牌。（有多少枚进张的"进张"一般是指降低向听的牌。不降低向听的牌一般被称作为"改良"。本文中也这样表示。）

例：<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/5m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/7m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/7m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/1p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/3p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/5p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/6p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/7p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/8p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/9p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4s.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/5s.gif' height='32px'> →打<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4m.gif' height='32px'>

即使摸到<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/6m.gif' height='24px'>，也比打<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/7m.gif' height='24px'>的时候摸到<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/6m.gif' height='24px'>之后的进张要广，所以这里打<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4m.gif' height='24px'>是正解（打<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4s.gif' height='24px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/5s.gif' height='24px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/5m.gif' height='24px'>的话进张枚数一样但是没有了<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/6m.gif' height='24px'>的变化）。但是如果只是因为摸到<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4p.gif' height='24px'>也会有断平三色的变化而去选择打<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/9p.gif' height='24px'>是错误的。（因为有一气通貫，打9p和打4m相比减少向听的有效牌（进张）明显比较差。）

## 重视对收支影响较大的因素

麻将中有很多种影响选择打牌的因素（大体可以分成形成面子、搭子的容易程度，形成的面子、搭子的好坏（听牌强度的好坏，打点）以及手牌的守备力）。但是实际上，很少有需要考虑多种因素的时候，大部分情况下只要考虑比较重要的因素就可以得出正解。如果要强行比较出所有的因素的话很容易打错牌。（上记的手牌中打<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/9p.gif' height='24px'>是一个好的例子。如果把比较的基准全列举出来的话，很容易区分不清是不是在胡乱比较。）

在做牌的时候是庄家还是闲家，或者是哪一个闲家这个因素并不重要，这点和上面所述的"只要考虑比较重要的因素就足够了"这个论点相一致。经常有人说庄家应该重视速度，虽然这个说法是正确的，但是这并不是因为庄家的打点是其他家的1.5倍，而是因为存在连庄，以及被自摸的时候失点是其他家的2倍这两个原因。

是庄家还是闲家在攻防判断的时候是十分重要的。这是因为庄家选择进攻还是防守，对是否连庄和是否会被自摸的影响很大，进而对收支的期待值也有很大影响。一方、手作り（特に序盤）の段階であれば、若干速度重視よりの選択をしたところで上記の要素が収支期待値に与える影響は相対的に小さい。（看不懂）因此无论是庄家还是子家，基本上可以只根据手中的牌来选择打牌。是南家还是北家这种差别基本可以无视。

北家は（鳴くと親のツモが増えるから）鳴くなという古い格言が存在するが、親のツモを１回増やすことによる親のツモ和了率の上昇と被ツモされた場合の失点が1.5倍となることの収支に与える影響は如何ほどのものだろう。（しかもこれは他の子の和了率が下がることは考慮していない。）（看不懂）

但是，比起其他的字牌要优先保留自风。如果他家同时在听牌，那应该尽量不要让庄家去摸海底牌。虽然这些因素对收支的影响很小，但是在这里没有比这更重要的因素了。就是说，要重视最容易影响收支的因素。

每一局的收支期待≠每一场半庄的收支期待，所以根据点棒状况有要重视和率的情况（如果比较难和牌的话则重视防守）和要重视打点的情况。但是点棒的状况也和上述的庄家和闲家的差别一样，在局数还剩下很多的时候（除了all last，all last前，已经没有庄家的大分差4位，以及有人即将被飞以外）并不需要特别的重视。麻将中在局数还剩下很多的时候就可以说稳拿1位的局面，以及在大分差四位的时候因为和了比较小的牌把局流掉导致后面反而特别难打的局面并不是太多。

## 一向听巅峰理论
在考虑牌山中什么牌比较容易摸到的时候，"场上万子比较多的话他家手中有万字的可能性比较低，因此摸到万字的概率比较高"的理论是正确的。但是因为摸到了万字，那么凭着气势觉得接下来也会摸到万字吧！，或者相反的觉得接下来会平均一下摸到索子或者筒子的想法是完全错误的。不只是颜色，对于数字，顺子和对子也是一样的。

在一次的自摸中，摸到可以降低向听数的牌（进张）的概率p可以用<code>（牌山里剩下的有效进张的数量）/（剩下的牌的总数）</code>来表示，摸到有效进张的平均巡目数大概是1/p。因此，在总进张数越少的时候一枚进张的价值就越高。

于是，从孤立牌的角度来讲，比起单纯的进张枚数，应该尽量让这张牌变成搭子时的进张要广；从搭子的角度来说，应该尽量让愚形搭子容易变成面子；从全体的角度来说，应当让离听牌越近的时候的进张越多。（因为离听牌越近有效进张的数量就越少）

例：<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/5m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/8m.gif' height='32px'> →打<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2m.gif' height='32px'>(<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/8m.gif' height='32px'>)

虽然<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2m.gif' height='24px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/5m.gif' height='24px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/8m.gif' height='24px'>中选择打<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/5m.gif' height='24px'>的话进张数量是最多的，但是为了更容易形成两面搭子应该选择打<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2m.gif' height='24px'>或者<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/8m.gif' height='24px'>。

例：<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/1m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/1m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/8p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/9p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/9p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/3s.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/3s.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4s.gif' height='32px'> →打<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/3s.gif' height='32px'>

例：有多于五个的搭子（搭子过剩）的时候应该打掉最弱的搭子

## 先制和牌的好处
麻将是竞争点棒多少的游戏。得点竞争类型的游戏中大致有两种战略：让自己得点和妨碍对方得点。虽然麻将中这两种战略也都存在，但是在麻将里妨碍对方得点的手段是十分有限的。避免放铳是一种有力的妨碍对方得点的方法，但是这并不能阻止对手自摸，或者对手从他家那里和牌。要想阻止这些情况，只有自己和牌这一种方法。麻将是可以通过自己得点来直接妨碍对方得点的。因此，除了被对方先制并且自己和牌困难，尽量避免放铳（弃和）是最好的选择以外的时候，基本上要争取和牌。高精度的牌效率是麻将必须的技术。