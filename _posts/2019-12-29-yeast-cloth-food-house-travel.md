---
layout:      post
title:      ".tex | 实验室中酵母菌的衣食住行"
keywords:   "酵母, 显微, 培养基, 培养液"
excerpt:    "实验室里的酵母，吃得怎样，住在哪里，过得好吗？"
date:        2019-12-29
categories:  post
milestoneID: 12
---

“酵母”其实是1500多种微生物的一个统称，但是在科学研究中最常用的一种是 _Saccharomyces cerevisiae_，下文中的酵母一词指的就是它们。作为一种单细胞生物，酵母在指数生长期，通过出芽生殖的方式，平均约90分钟就可以繁殖一代。同时作为真核生物，核膜以及各种具膜细胞器应有尽有。而且酵母对脂质的代谢路径和人类的代谢路径在进化上是同源的，也就是说有些治疗人类疾病的药物，也可以在酵母细胞中产生效果。结合酵母菌快速繁殖的特性，可以方便相关药物的筛选。再加上人们熟知的发酵、酿酒等应用，酵母就成了生物实验室中非常常见的一种模式生物。

## “衣”

~~全裸，下一题。~~

这个问题其实还是可以再多说两句的。

这里的“衣”显然是一种比喻，既然是比喻，那就要看说话的人想强调的是衣服的哪种性质。酵母的细胞膜外面还有一层细胞壁，对于一个细胞的定义来说，细胞壁并不是必需的。从这个角度讲，完全可以把细胞壁比作酵母的外套。这层外套的主要成分是糖类，既包括起到结构支撑作用的多糖，也包括传递信息，可以用来对酵母进行特异性识别的糖蛋白。

即便有了这么一层外套，单个的酵母细胞在显微镜下依然是透明的，在普通的亮场 (bright field) 显微镜下，可以隐约看到酵母细胞内部比较巨大且明显的结构，比如液泡。要想看得更清楚，就得用上 DIC（微分干涉相差，differential interference contrast）显微技术了。要说清楚 DIC，需要一篇独立的文章，而文章的很大一部分都会是数学。简而言之，光在不同的介质中的传播速度不同，表征介质的这一性质的物理量叫做“折射率”，折射率 × 光传播的距离 = 光程。当我们让两束相同的光线，通过给定的距离，其中一束光线通过我们的酵母细胞，另一束经过一段折射率已知的均匀介质（比如说空气），两束光通过的光程不同，再次见面时就会有差别，用衍射的方法比较一下两束光，就能得出酵母细胞内不同位置的折射率信息，从而看出不同的结构。

DIC 设备比普通的亮场显微镜要贵不少，而且有些不同的细胞器其实长得很像，即便用上 DIC 也不容易分清楚，这时候我们就要对酵母细胞本身动点手脚。有些荧光染色剂可以和某种细胞器特异性地结合，用特定波长的光照射细胞，被染色的细胞器就会发出另外一种波长的荧光，我们用滤光片把入射光过滤掉，就可以得到这种细胞器在细胞中的位置、形状和大小信息。除了用染色剂，还可以把荧光蛋白基因插入到某些细胞器蛋白质的基因旁边，这样就免去了每次观察细胞时染色的麻烦。~~（“所以你们实验室做转基因喽？那你告诉我，转基因食品能不能吃？”）~~

之前两段说的是单个细胞，而在固态的培养基（“住”的部分会介绍）上面，酵母细胞不能大范围移动，单个酵母细胞作为祖先不断繁殖，“子又有孙，孙又有子”，久而久之（其实也就两三天）就可以形成一个菌落，就是培养基上一个肉眼可见的斑点。不论是黄色的 YPD 培养基还是白色的 SD 培养基，菌落的颜色肉眼观察不出区别，都是乳白色。

## “食”

酵母是一种异养生物，也就是说需要摄入营养物质，既要利用其中的化学能维持自己的生命活动，也要利用这些物质的原子和分子构建自己身体的组成成分。能够满足微生物细胞生长繁殖需求的营养物质，叫做培养基 (medium)。我们实验室中常用的培养基主要就两种，一是 YPD 培养基，二是 SD 选择培养基。

### YPD

这个名字直接来源于其成分——Yeast extract, Peptone, Dextrose——酵母提取物、胨、葡萄糖。用酵母提取物去喂酵母……不能多想，想多了就有点怪怪的……好处是真的好用，生长速度比下面要讲的 SD 培养基要快一些。而且由于我们实验室都是 SD 选择培养基，所以野生型酵母只能用 YPD。

那么缺点呢？一个问题就是酵母提取物里面，究竟有什么物质，每种物质占比多少，都是一笔糊涂账，实验结果就不好分析。

另外，YPD 培养基在很多波长的光照射下都会发出微弱的荧光，在之前说过的荧光显微观察中，这种荧光就会成为背景噪声。所以 YPD 培养的细胞不能直接进行荧光显微观察，要换到 SD 培养基养一段时间（一般半个小时以上），或者干脆就直接养在 SD 培养基里。

### SD 选择培养基

SD 的全称是 synthesis defined，意思是人工合成，而且成分是明确且固定的，配方在一般的科研网站上都能找到。而选择培养基的意思是，相比于普通的 SD 培养基，某种营养物质（一般是某种氨基酸）被去掉了，比如说 SD-His 培养基中就不含有组氨酸 (Histidine)。这些营养物质都是野生酵母没办法自己合成的，但是在用同源重组的方法进行基因编辑的时候，我们除了会导入目标基因之外，还会一起导入能表达合成这一营养物质的酶的基因。把被编辑过的细胞接种在选择培养基上，那些没能成功编辑的细胞将无法合成相关营养物质，只有编辑成功的细胞能够幸存，并形成菌落，这就是“选择”一词的由来。

## “住”

由于酵母既没有嘴，也不像草履虫一样拥有可以游动的鞭毛，所以只能和营养物质生活在一起。（当然也是和代谢废物生活在一起，不能多想……）所以说，培养基不仅是食物，还很类似于酵母菌的“家具”。

前面说到了培养基，定义里说是营养物质，但是并没有强调其物质状态。培养基既可以按照配方配置成溶液，这叫做液态培养基。在溶液中按比例（一般是 2% 的质量分数）加入琼脂 (agar)，先加热溶解，然后稍微冷却之后倒入培养皿 (petri dish)，继续冷却就形成了凝胶，这样就制成了一个半固态培养基。

在培养基中加入了细胞之后，此时的混合物应该叫做培养液 (culture)，如果把 medium 和 culture 弄混了的话，有些人的脸上会浮现出微妙的笑容。屠格涅夫说过：“有教养不是吃饭的时候不洒汤，而是别人洒汤的时候你不去看他。”为了避免别人没有教养，我们还是应该勉为其难地区分一下这两个概念。:-)

说完家具来说房子，也就是 culture 的容器。

在液态培养液中，酵母的密度要略微大于培养基的密度，所以长时间的静置会使得细胞在容器的底部沉积，影响生长速度。所以我们需要把容器固定在恒温的机械平台上不断摇晃，为了让离心力尽可能地大，容器要选用底面积比较大的锥形瓶，用普通试管的话需要将其斜放。~~（我看看有哪个高中生蹦出来说不存在离心力这回事，哼）~~

对于琼脂培养基，培养皿直接放在恒温箱里静置。前面说过，单个细胞会繁殖，然后无法移动，形成一个菌落。没有基因突变的话，这一个菌落中细胞的基因型都是相同的。如果两个空间上相邻的菌落不断长大，就会连在一起，进而长成一个大菌落（突然想到了光学课本里瑞利判据那张连环画），此时就不好确定基因型的纯洁了。在长到这种情况之前，就要把培养皿用 3M 胶带封起来，然后放到低温下暂存，等待日后实验时取出单个菌落继续培养，或是冷冻长期保存。

说到了温度，酵母菌的正常生长需要 30 摄氏度。刚才说到要保存菌落已经足够大的培养皿，这时的温度一般是 4 摄氏度，也就是冰箱冷藏室的温度。而长期保存细胞的话需要放入 -70 ~ -80 摄氏度的低温冷柜中。

## “行”

我们实验室还并没有厉害到需要给其他实验室寄送我们培养的菌株的地步，我们实验室里的菌株是怎么来的我也忘了……所以这一节所说的“行”，指的是酵母菌在不同的培养基之间的转移。

网上的教程里比较讲究，啥高科技工具都有，就跟吃螃蟹的蟹八件似的。我们实验室比较莽，不论是冷冻的细胞，还是液态或者琼脂培养基中的细胞，一律都是用消毒杀菌过的细木棍来取细胞，如果不是要转移到琼脂培养皿的话，甚至还可以用一次性移液枪头。琼脂培养基的话要仔细蘸一蘸，确保取到的细胞来自同一个菌落，冷冻细胞的话就刮一刮容器里的冰沙，液态培养基的话就随便蘸一蘸。

如果目的地是液态培养基的话就很简单，木棍伸进去，搅合搅合，完事儿。

如果是琼脂培养基的话，要轻轻地在琼脂表面来回涂擦，要小心不能刮坏琼脂层。来回涂擦几次之后，把木棍换到之前没接触细胞的一面，在刚才涂擦的区域边缘，往没涂过的地方来回涂擦几次，如是反复者二三。这样做是因为刚开始的细胞数量可能比较多，长出来的菌落从一开始就连成一片，后来几次涂擦时细胞的密度就会越来越低，某个区域就会出现足够数量又相距足够距离的一群菌落。总之是个技术活还是个经验活。

如果是新制备长期保存的细胞的话，需要先在液态培养基中将细胞养到合适的浓度，然后在专用的容器中按照 1:1 的比例混合培养液和甘油，然后就可以放进冷柜了。