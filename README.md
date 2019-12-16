# :whale2: DataStory_Interactive-Visualization :whale2:

Seeking True from Fact 网新人，有态度，不认输，不头秃

## :hammer: 定义数据产品

- 广义来看，数据产品是可以发挥数据价值去 **辅助用户更优的做决策（甚至行动）** 的一种产品形式。
- 狭窄来看，淘宝数据魔方、百度指数、电商的 CRM 平台、各种公司内部的数据决策支持系统等都是数据产品，是已经有成熟的后台来进行数据统计的可视化

```diff
+ 所以基于上面我认为要来用数据产品来讲好数据故事的难点就是在于怎么来把握一个核心，也就是找到用户的 **真正核心需求、痛点**
```

## :wrench: 定义数据可视化
- 信息可视化(Infographic（Information Graphic）) **更注重艺术效果**，它是具体化的、独立的、需要手工定制的。并没有任何一个可视化程序能够基于任一数据生成具体的图片并在上面标注解释性文字
- 数据可视化[data visualization] **具有更广的普适性**，同一类图表并不会因为数据不同而改变自己的展现形式，用户通过对数据进行可视化的应用来搭建报表。例如 [网易有数](https://youdata.163.com/)

```diff
+ 所以基于上面我认为数据可视化是需要在洞察用户核心需求痛点的前提上，使用数据分析的形式，将数据故事呈现在图表中，并且判断出相关性与其结论，给出合理的建设性意见和解决办法
```

## :bulb: Ptich DataStory

- 价值主张:分析 **世界500强企业中美经济结构的差异化** 现象，结合数据分析图表 **展示差异化因素**，并在最小可行性 **推断未来新兴科技发展方向**
    - 数据故事：世界前500强公司的上班名单中中美占比较多且与其他国家不在同一个档次上具有 **鲜明的可比性**，并通过逐年的发展趋势可预测未来新兴部分技术的发展前景
    - 数据产品：使用**交互可视化工具 Plotly/Pyecharts，搭建 Flask 框架实现可互动交互界面**，并且呈现数据故事引导用户对数据进行思考
    
- 数据来源: 
    - [2019 年财富世界 500 强公司排行榜](http://www.fortunechina.com/fortune500/c/2019-07/22/content_339535.htm)
    - [2019 年世界 500 强 129 家中国上榜公司完整名单](http://www.fortunechina.com/fortune500/c/2019-07/22/content_339537.htm)
    - [胡润研究院发布《2019 胡润全球独角兽榜》](http://www.hurun.net/CN/Article/Details?num=E7190250C866)


## :calendar: 产品进度

- :ballot_box_with_check: 19.12.13-**19.12.15 数据产品或者是数据可视化项目的点子放在Github上面**，将url填在腾讯文档上面，在12.15周日晚23点之前提交
- :black_square_button: 19.12.15-**19.12.18 组建团队**
    - < 15Days Pitch DataStory Product in PRD-MD to GitHub 
    - < 15Days Show python ability in Jekyll to GitHub
- :black_square_button:19.12.18-**19.1.05 提交最终 url** 19days is enough but we should in advance to spend time in holiday
    - 12.18-12.22 实现见评分要求
    - 12.23-**12.29 结束最终 url 放假** 最终提交各自负责的入口url进行项目及文档提交
- :black_square_button:19.1.06-**19.1.07 互评阶段**，要求见评分要求

> 共同作品要求：
1.自己提供数据，但数据量>250个
2.Html5界面设计包含CSS样式
3.必须部署在 pythonanywhere 并可用

- :black_square_button:19.1.08-19.1.10 互评公示及异议，要求见评分要求

## :warning: 评分要求

18级评分点：
- 实现 **交互功能** (Html表，至少做到表的交互没图假设下)
- 实现 **部署在 pythonanywhere 可用
- 基本README.md技术文档总结项目说明
  - 代码 **GitHub URL**
  - **pythonanywhere url**
  - **数据传输描述**
- 基本交互功能 **Html控件使用丰富**(加分项)

17级评分点：
- **数据清洗和收集难度，数据集丰富程度**
- **交互功能**对于强化数据产品或者数据故事**表现力的程度**
- 交互界面 **美观得体**(使用Pyecharts、Plotly、CSS包含在内)
- 整体数据产品/数据故事是否**有洞见**，给用户交互产生洞见的引导及可能性

简述之：
- 共同要求：hurun数据/自己提供数据-国家统计局+H5页面设计包含CSS样式+pythonanywhere.com，是否有说服力和数据洞见-数据库,Flask
- 18级评分：交互功能能否实现最基本的数据传递+是否上传到Pythonanywhere(最终提交github和pythonanywhere网址)+交互功能的丰富性(加分项)
- 17级评分：交互功能对于强化数据产品或者数据故事的程度+交互界面是否好看plotly、pyecharts、网页CSS等渠道实现都可+数据产品/数据故事是否有洞见+数据清洗和收集难度，数据集丰富程度

## :checkered_flag: 产品目标及技术栈

## :computer: 开发人员:

- 前后端(基本：仅表)交互的代码实践及文档写作
- Html文档结构及交互控件实现及交互变数实践

### :bar_chart: 产品经理/交互设计师：

- 最小可行性的交互式数据可视化产品设计
- 完成PRD及至少2份成功交互且交互意义相关联（以超链接活交互达成）的交互式界面(至少1份含地图)的产品原型或完整产品，包括使用Pyecharts/Plotly模块等整合外观样式及数据科学代码实践，外观样式前端CSS及JS库的调用实践(Bootstrap)


## :two_men_holding_hands: 合作伙伴

- :raising_hand: 有担当，共进退
- :ok_woman: 知道如何实现 Flask ，成功独立搭建过 Flask 框架，可以一起回顾，熟悉 html、css 更好，懂得如何处理数据链接和前后端响应
- :person_with_pouting_face: 对产品负责，且有自己想法
- :octocat: [https://gitee.com/NFUNM065](https://gitee.com/NFUNM065)
- :telephone_receiver: 18933815383 wx同号

链接：

- [胡润研究院发布《2019 胡润全球独角兽榜》](http://www.hurun.net/CN/Article/Details?num=E7190250C866) 直接复制粘贴Excel数据表里面
- [胡润研究院发布《2019 世茂西山龙胤・胡润全球富豪榜》](http://www.hurun.net/CN/Article/Details?num=0C89B7A101E0) 文末有榜单可下载
- [18 第二季度胡润大中华区独角兽指数](https://www.hurun.net/CN/HuList/Unilist?num=ZUDO23612EaU) 数据比较旧
- [胡润研究院发布《2019 LEXUS 雷克萨斯・胡润百富榜》](https://www.hurun.net/CN/Article/Details?num=DB69EC68030F)没有时间和地点比较难做数据化
- [福布斯排行榜](http://www.forbeschina.com/lists)
- [财富](http://www.fortunechina.com/fortune500/node_65.htm)
- [2019 年财富世界 500 强排行榜](http://www.fortunechina.com/fortune500/c/2019-07/22/content_339535.htm)


--- OVER ---
