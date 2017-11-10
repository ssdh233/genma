## 孤立牌和单独搭子

麻将每一巡会打掉手中最不需要的牌。为了判断哪张牌是最不需要的牌，本战术论从本节开始考察孤立牌和搭子的优先度。这里的优先度的判断基准是门清的情况下构成四面子一雀头的容易程度，因此如果没有特别的条件的话，默认门清并且打点上没有差别。

### 手牌各部分之间的比较
再摸n枚有效牌就可以听牌的状态叫做n向听。无论是什么样的手牌，只要把孤立牌摸成6个对子就可以七对子听牌，所以n的最大值是6。（面子手的向听数最大值是8，只考虑国士无双的话最大值是13。）为了和牌首先必须要听牌，为了听牌首先必须要一向听...所以减少向听数是非常重要的，如果可以减少向听数的话那么基本上应该选择可以减少向听数的打牌。

减少向听数的行为可以大概分成以下三种。（这里只讨论面子手的情况，如果不加特殊说明以后提及向听数的时候都是指面子手）
* (1)把孤立牌做成搭子（面子候补不足的时候）
* (2)把搭子做成面子
* (3)把孤立牌做成雀头（如果已经有雀头则看成(1)）

与此相反，增加向听数（向听倒退）的行为有以下三种
* (1)面子候补不足的情况下拆掉搭子
* (2)拆掉面子（搭子充足并且没有雀头的情况下，1123m中打掉2m固定1m的雀头这种不算）
* (3)拆掉唯一的雀头

因为344m这样的复合搭子在没有其他雀头的时候就不能被看成复合搭子了，所以（除了搭子过剩时以外）从344m11p中打掉1p也算向听倒退。不过这样打剩下的手牌中也还有雀头，所以这种打牌被算成(1)而不是(3)。相反，即使在没有其他雀头的时候，如果选择固定雀头时面子和面子候补会减少的话，那么(3)拆掉雀头则不算作是向听倒退。（见下例）

例：
<p>
<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/1m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/1m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/3m.gif' height='32px'> -> 打<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/1m.gif' height='32px'>
</p>
<p>
<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/3m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4m.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2s.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/3s.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4s.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/5s.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/2p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/3p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/5p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/9p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/9p.gif' height='32px'><img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/9p.gif' height='32px'> -> 打<img src='https://raw.githubusercontent.com/matsumatsu233/mahjong-pai-converter/master/sources/mj-tactics/4m.gif' height='32px'>
</p>

为了做出更强的搭子而选择(1)的情况还是有一些的，不过基本不会选择(2)(3)（最多就是为了做出新的手役的时候），(2)(3)一般情况下都是亏的。因为雀头比面子好做，所以拆掉雀头(3)比较有利的例外情况比拆掉面子(2)要多一些（虽然都很少）。

综上所述，手牌中各部分的优先顺位是，孤立牌<<搭子<<<唯一的雀头<<<面子

※不等号的基准

* <<<  完全的上位互换
* <<   基本可以形成上位互换。在特殊条件下也有逆转的时候。
* <    差距比较小。根据手牌中其他部分的形状和牌河的状况很容易被逆转。


### 孤立牌之间的比较
字牌（客风）<<1・9<<2・8<<3~7<<<3445和3456这样的形状（有4种可以形成两面的进张）

考虑赤宝牌的话，3・7<4・5・6，其中46摸到赤宝牌可以形成两面，5比较容易做出内嵌张。

考虑手役和鸣牌的话，役牌对子至少和两面一样强。单独的19没有办法做成两面，单独的28可以做成一种两面，所以基本上是1・9<孤立役牌<2・8。不过，这个根据手牌中其他牌的形状很容易被逆转（门清越难和的时候，孤立役牌的价值就越高）。

### 单独搭子之间的比较
边张<<外嵌张<<内嵌张<<<两面

考虑赤宝牌的话，内嵌张之间35・57<46，外嵌张之间13・79<24 68。听牌的时候越靠边越容易和，所以没有赤宝牌的话顺序就反过来了。

考虑赤宝牌的话，23・78 < 45・56 < 34 67。没有赤宝牌的话根据听牌的强度45・56< 34・67 < 23・78。

外嵌张以及比外嵌张强的搭子都包含3~7，所以可以和孤立牌的3～7形成上位互换；边张包含28，所以可以和28形成上位互换。但是边张和3～7没有办法这样比较。边张和3～7很难单独拿出来比较，不过基本上可以认为3～7<边张。（在12巡以内，边张更加容易形成面子。一局只有17～18巡，即使是序盘也要重视在“较早的巡目内做成面子的容易程度”而选择边张。不过这个比较容易因为手牌中其他部分的形状和牌河的状况而变化。）