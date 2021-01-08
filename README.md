写于19年底，请考虑时效性

大致分为时间线、简历、刷题、公司分析和建议几个部分。适合像我一样找工向、陆本、之前没有大厂实习、转专业的同学阅读

## 时间线

这里分享一下我自己的时间线供参考

7月前：刷题、做项目、实习。这些开始的越早越好！申请季一直焦虑无益，不如早日为找工做准备

7-8月：写简历、改简历，同时兼顾刷题和做项目

8-9月：开始投简历，一般来说越早越好，尤其对FLAGUAP等公司（后面详述）

9月及以后：面试，刷面经同时继续投简历，刷题保持手感

## 简历

个人认为，在当前形势下，简历在找工作中非常重要，甚至超过了刷题，因为如果过不了简历关，把LC刷穿也没有用武之地。所以在找实习季开始前，也就是七八月左右，请准备好一份不错的简历。

个人认为，“不错的”简历有以下几个方面，可以尽量去满足：

1. 国内大厂（BAT等）和外企分部实习（MSRA等），如果没有的话，小厂的实习也是可以的，最好在来之前做1-2段实习，这样比全是toy projects的简历要好很多。

2. 流行的技术栈及相应项目。比如前端react、后端spring全家桶，大数据相关的hadoop、spark，还有aws相关等等。我的实习和项目大多是web全栈，中间穿插了一些简单的cache、distributed system、cloud computing等，从结果上看，效果还挺不错的。

3. 优秀的表述。这是很重要的一点，很多简历只是写自己用什么干了什么而没有具体的impact，这样就很空洞且没有亮点，所以请好好想想自己的贡献和impact，最好量化表示，比如降低页面加载时间、提高访问量等等，可适当润色。

4. 无懈可击的格式、语法、细节等。个人推荐把简历分为education、technical skills、work experience和projects四个部分，其中education和skills加起占1/3左右，剩下的大头应该是work experience和projects，每个project和work experience大概3-4个bullets，每个bullets不要超过两行也不要少于半行，且都以动词开头（implement/build/create/design/use等等），注意描述中带上技术栈和相应的impact。日期、地点等细节一定要注意，如果被发现有错误会大大减分。

5. 反复的修改。像申请一样，找实习和工作的简历标准要求更高，所以需要不断修改优化。可以找学长学姐问问建议，看看地里求改简历的帖子，语法上可以请学校的career center看看。同时，新做的更好的项目可以实时更新在简历上。

6. 针对不同厂、不同job description准备不同简历。比如偏前端一份、偏后端一份。按照job description里的qualification调整简历的skill、work experience和projects部分，而不是一份简历投天下，这样的话拿到面试的概率会大大增加。

## 刷题

地里有很多刷题方法和总结，我这里只提供一些tips：

1. 推荐python刷题。因为上手简单、代码量少、速度快。而且由于代码量少，出笔误等小bug的概率也会降低。尤其是对解题速度有要求或者follow up很多的公司，python优势更加明显，而且大部分科技公司都是接受python的

2. 关于刷题顺序。个人推荐在时间不多的情况下，一开始可以按照类型刷题，保证基础的数据结构和算法都做到过，拿到面试后再刷该公司的tag题

3. 合理分配时间。没有必要花大量时间在某些hard题（比如Basic Calculator IV等）或者不常规的题上。如果一道题想了十几分钟没思路就去看discussion，因为在真正的面试里，一道题也不可能留给你更长的时间去思考。通过合理分配时间，刷题效率会大大提高

4. 不要只贪量，而需要做到总结归纳、举一反三。LC上有很多题其实是大同小异的，比如union find、sliding window、binary search一种思路就可解决很多道题，面试里也经常考到，所以不要只是把solution复制粘贴跑过就算了，对于经典的题目务必要理解透彻并且能分析时空复杂度

5. 边说边写，也就是在写代码的同时用英语说思路。大多面试都鼓励甚至要求think loud，这样可以体现你的沟通水平并且帮助面试官理解代码。这一点对初刷题者可能很困难，但是是一个必须经历和适应的过程，需要不断的锻炼

6. 该刷多少题呢？这个问题因人而异，个人认为，如果能在LC正常的contest里稳定做出3-4题，就足够应付大多数面试了，此时可以把重心放到其他方面，同时每天刷两三道保持手感

## 公司分析

1. Facebook
个人认为Facebook最难的是简历关，而且Facebook对于学校和diversity具有明显的偏向性，lz所在的哥大拿到面试和offer的人很少，据我所知cmu、ucsd也是如此。由于Facebook对每个学校有配额，那么在一个人少的学校或是Facebook喜欢的学校拿到面试的概率会大大增加。neu sv和seattle一直以来都受Facebook青睐，而其他学校则取决于当年负责的hr，比如去年的jhu、今年的uci等等（如有错漏敬请指出）。而且Facebook招人早且比较集中，所以尽量早投。Facebook爱考tag题且看重bug free，面试也略玄学。

2. linkedin
LinkedIn每年发的面试并不多，但面试大都是原题，我在准备的时候翻遍了地里的面经，基本所有题都出自LC的LinkedIn tag，所以拿到面试就意味着已经成功了一大半，那么如何才能拿到LinkedIn面试呢？

首先是要早投！LinkedIn每年招人很少，所以招人窗口期很短，那么请提前找好内推把简历发过去，并在LinkedIn上设置提醒，保证position一放出第一时间内推！
然后是多投！和其他厂不一样。LinkedIn把intern划分的十分细致，我知道的就有SWE、Systems & Infra、UI、ML、SRE、DS、Big Data等很多个分支。那么如果同时投多个岗位拿到面试的概率会大大提高。我今年看到LinkedIn的SWE intern申请人数是15000+，而UI和Systems & Infra都只有1500左右，但我不觉得SWE intern的hc能有另外两个的十倍，所以很显然，如果你有相关背景，在SWE intern外同时投其他track拿到面试的概率会大大提高！我自己SWE intern简历拒，但是UI和Systems & Infra都被捞起来了。其实偏前端的简历本来就可以直接拿来投UI，而偏后端的简历加一点distributed system、cache、message queue等等相关技术就可以投infra了…而且其他大部分track的面试主要还是算法，地里也有很多面经可以用来准备。

3. Amazon
今年亚麻爸爸正常发挥，身边人基本都有面试。个人感觉只要简历好好写并且几个OA准备好的话拿到面试还是不难的。至于玄学vo，我自己没有面所以就不分享了，地里有很多很好的经验分享。

4. Google
个人感觉Google今年的面试也没有非常好拿，身边投晚了的同学很多就没有面试了。所以不要因为Google题难就想一直拖着准备，请先内推拿到面试，面试可以约晚一点。而且Google的流程很慢，如果进pool晚了的话很可能最后就淹死了…
Google面试总体是偏难的，不是抱佛脚刷几道LC就能应付的。因为Google出原题少，刷题时归纳总结、举一反三就更为重要。

5. Uber
今年Uber发面试也不多，简历关也挺难过的。因为Uber比较喜欢Golang，简历上如果有Golang相关的技术的话会比较好，如果没有的话就Java吧。
面试总体比较平和，比去年整体难度要低一些且大都是原题。所以有时间的话把tag题都过一遍就比较稳了。

6. airbnb
作为即将ipo的hot startup，Airbnb难度自然是极高的。体现在面试不好拿、技术面难和bq面玄学上。
首先Airbnb面试发的并不多，貌似对哥大比较友好，不过由于难度很大，最后能收到offer的同学也不多。
Airbnb技术面题很难，虽然基本都是原题，但是大都是hard级别且有follow up，貌似也要求bug free当场跑通的，所以如果要通过技术面，需要把Airbnb面经上所有题及follow up和时空复杂度完全吃透，并且遇到一个nice的面试官才可以。
Airbnb的bq面（cross functional）挂人也不少（比如我），地里有同学整理好了面经，需要准备好相应的故事能怼上去，同时需要熟记并理解Airbnb的culture、value和mission，表现出自己非常match。剩下的就听天由命了。

7. Pinterest
P家今年发的面试也不多，而且感觉刚开始就结束了，像这样的公司最好也早投，剩下的就看命了。

8. Intuit
为什么要把intuit放在这里呢？因为他家面试真的很简单，很适合提前拿到保底。但是因为官网上没有放出来intern，很多人就没有投。其实Google一下intuit software engineer intern的第一个就是了。OA和技术面都是外包给karat的, 常见的就两三道题，都有很多面经可以准备。然后就是一轮value面了，这个面试比Airbnb的cross functional要简单很多。HR会提前发给你他们家的value，然后只会挑四五个value问你有没有例子支持，所以准备起来很容易，通过率也比较高。

9. Dropbox
Dropbox貌似海投比内推更有用一些，而且最好也要早投，OA都是一样的auto complete，电面和onsite的题都是那几道原题反复出，不过会有多种多样的follow up，所以也需要真正吃透面经题和已有的follow up，剩下的就看运气和自己之前的积累了，沟通交流能力也是很重要的。

10. Microsoft、Bloomberg
感觉这两家都比较喜欢在career fair上发面试，Microsoft甚至只在career fair上招实习。所以需要准备好简历好好和recruiters聊天，切忌把简历一扔就走了（比如我）。因为我都没拿到面试，就不多说了。

剩下还有一些小众或者发面试很少的公司比如Stripe、Oscar health、Quora、Twitter、Tripadvisor，我就不再多说了。

## 建议

分享一些我自己觉得很重要的tips：

1. 早投！很多公司投晚了就没坑了甚至关闭申请了，最好能一开就投！

2. 多投！和申请一样，广撒网总没有坏处，何况还不要申请费。我一整个找实习季投了几百家公司了，大公司找内推，小公司直接海投。可以在LinkedIn上按时间排序投刚放出来的intern，这样拿面试的概率更大

3. 不要选太多硬课。找工本来就很花时间了，如果再上几门硬课的话更会应接不暇。

4. 心态。找工对大多数人来说是一场持久仗，不是说收到哪家拒信天就塌了，更不用在哪一棵树上吊死。即使过程中会受到无数的打击，也要相信只要坚持下去肯定会有好结果的！大厂不行投小厂，小厂不行投国内，找不到实习提前准备全职。当收到offer不再欣喜若狂而是觉得理所应当的时候，就是它该来的时候。在这个过程中该吃吃该睡睡，千万不要因为焦虑伤了身体。

5. 运气（人品）。这点比较玄学，不过我真的感觉运气和自己的行为是有一定关系的。所以请保持善心，多多帮助别人、分享信息。挂了面试就当是攒人品，过了面试也不要高兴过头，相信人品是守恒的而且越努力越幸运~

最后祝申请和找工的同学们offer多多，一切顺利！
