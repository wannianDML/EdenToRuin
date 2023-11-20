# EdenToRuin
an vic3 mod.

don't know english.
所以以下内容仅使用中文，不擅自做英文译本。

[h1]MOD目前完成度四舍五入等于零[/h1]
[h1]仅仅是“能玩”[/h1]

[hr][/hr]
特别感谢MOD 创意基石：https://steamcommunity.com/sharedfiles/filedetails/?id=2897798256
本MOD基于此修改制作。
感谢它帮我从一团乱麻中找到了线头。
另外文末更新日志之上有我学习时整理的一些资料和笔记附赠。

[hr][/hr]
MOD含有以下元素，请谨慎游玩：
——缝合了很多作品的设定，且并未做严格的考证。
——大量的二设、三设，同样未做考证。
——大量私设：来自个人曾写过的随笔的if线。
——角色OOC、死亡描写、行为臆测。
——（可能的）反人类行为（指在道德观念上非人不能和人相提并论）
——不平衡的设计
——脱离现实的“现实设定”

【很多笑脸图标：不会美工，所以用了P社随机的占位符，图片和实际没有任何关系。】

第一次制作mod，很多部分会重做或大修。
关于地图和地形：除了原著中有明确说明方位的，场景位置都是自己的私设。比例是肯定不对的，日后再修。
有些地方叫做xx湖却是陆地：没做地形，日后更新。
战略区域：以比较著名的地标为战略区域的名称，辨识度高一点。
省份划分：参考原著，凭感觉分的。
初始人口数量：乱填的。
文化与宗教方面：这个多看几个特质应该能明白设计思路。
国家，领地：私设重灾区，基本不遵循原著。
旗帜：根本没做，都是P社随机的。

[hr][/hr]
大概是一个讲述高歌猛进，然后迎来终末的故事。
结局是注定的——但是你可以将它无限期推迟。

作为国家意志，写下剧本？
还是成为史书上的芸芸众生，粉墨登场？
亦或是干脆看着台上演出的revue，睥睨着starlight？

[h3]为和平的努力都失败了，现在，准备战争吧。[/h3]

[hr][/hr]
关于本MOD，以下所列无需询问许可：
①

关于本MOD，在满足前提下，无需询问许可：
①包含MOD本体文件的二次修改。（需在发布页提供修改内容对比）
②基于MOD本体的添加内容。（需在发布页说明添加内容）
②非盈利的再分发。（标注steam创意工坊链接，以及对应分发版本的版本号）

关于本MOD，禁止做的事情：
①利用本MOD以任何手段进行牟利。

关于参考资料 & 参考代码（主要部分，还有很多东西没记录就忘记哪来的了）（部分随时间流逝可能变得并不准确）：

#分类
链接 | 标题（注释）

#对其二次修改来进行练习
https://steamcommunity.com/sharedfiles/filedetails/?id=2897798256 | 架空基石（直接移植了此mod的文件）

#通过一些简单的实践来入门
https://tieba.baidu.com/p/8110393724 | 关于制作作弊法令、作弊决议、提高单日建筑进度等（“提高单日建筑进度”已过时）
https://www.bilibili.com/read/cv19478572 | 维多利亚3 mod 制作与研究（这个里面提到的时间倒着走不能用，会出恶性bug）
https://tieba.baidu.com/p/7814296844?pid=143920134841&cid=#143920134841 | 修改党+秘籍，希望对大家有帮助！
https://www.bilibili.com/read/cv19804629 | 维多利亚3 人口属性[1.0.6]

#进阶的资料
https://vic3.parawikis.com/wiki/模组制作
https://vic3.paradoxwikis.com/Modding （比上面全，而且也有实例，但是是全英文，如有必要建议使用baidu翻译桌面版进行截屏翻译）

#东方project的参考来源
https://www.bilibili.com/read/cv6051858/ | Zunglish(zun式英语)词典
https://thwiki.cc/ | （原作、二创、考证设定参考）
https://bbs.nyasama.com/ | （原作、二创、考证设定参考）

更新/计划日志
【等待修复】
1.gensokyo就算接壤，同一市场也不算作陆路相连。
——2023年11月19日——
【修复】
0.修正写错的代码与文字描述。 = √
1.修复“地灵殿”未出现在旧都。= √
2.修复“私人军事承包商”的“业务范围——>军事援助公司”判定条件。 = √
3.修复“八云”未拥有“虚镜”科技。= √
4.修复“effect_gensokyo_common_country”的继承逻辑。 = √
【改变】
1.为部分科技添加了增加“士兵政治力量”、“军官政治力量”的修正。 = √
2.为部分科技添加了增加“官僚政治力量”、“学者政治力量”、“工程师政治力量”的修正。 = √
3.科技“非常识之物”不再是一个可研究选项。 = √
——2023年11月15日——
【新增】
1.补全chinese本地化键值 = √
2.添加关于加快建筑的debug决议 = √
【删除】
1.删除赘余代码 = √
【改变】
1.适配正式版V1.5.7 = √
-校对被改变的modifiers名 = √
-校对static_modifiers文件 = √
-校对defines文件夹 = √
-校对buy_packages文件夹 = √
-校对th_common_building_groups.txt = √
-校对08_monuments.txt = √
-校对00_subject_types.txt = √ （删除了MOD重写的部分）
-校对eras文件夹 = √
-校对state_regions文件夹 = √
-校对pop_needs文件夹 = √
2.应用采用了新算法的th_buy_packages = √
-关于政治力量①：等于一个pop维持生活水平花费的万分之一； （这个有考虑修改，比如在这基础上提供一个1的增值。或是0.3减值？）
-②无任何修正的情况下，一个水平60的pop约等于216个水平10的pop；
-③那么其话语的“分量”理所应当的等于216个水平10的pop。
3.降低era1到era9科技花费 = √
4.cultures文件夹内文件重命名(th_+ -> th_cultures_+) = √
【修复】
1.修复gensokyo各地区没有文化本土 = √
