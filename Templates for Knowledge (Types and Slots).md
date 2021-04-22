# 知识模板（类别与槽位）

## 原因

明白什么东西属于某个“概念”是十分有用的。比如说，知道线粒体属于细胞器，“概念”是一种Rem，而碳是一种化学元素。

为了描述这种关系，我们一般称线粒体是一种细胞器，或者说线粒体是细胞器的一个“子类”。

遇到一组同类的概念，可能只需要问一组相同的问题。我们可以把这一组特定的问题组织成一个模板，应用于特定类型的知识。比如，我们可以像下面这样写出关于算法的模板：

- 算法：解决特定问题的固定步骤，对每个输入给出特定输出。
  - 解决什么计算问题
  - 步骤
  - 运行时间

这样关于某种特定种类Rem所想知道的一项属性，被称为一项“槽位”。模板的每一槽位一般都是Rem的“描述”。比如，下面介绍如何填写贝尔曼-福特算法的各个槽位。

- 贝尔曼-福特算法
  - 解决什么计算问题：单源最短路径计算问题；
  - 步骤：（略）
  - 运行时间：（略）

在RemNote中，任何Rem都能作为另一Rem的子类。RemNote能够理解Rem之间的包含关系，自动推荐父类的各个槽位。建立这种模板，你便知道自己需要学习什么，从而帮助学习相似的概念。你也可以学习更多关于特定种类概念的高级技巧，比如，通过回顾算法的[[解决什么计算问题]]、[[运算时间]]以及应用算法的复杂程度部分，你能够学会判断是否一算法能够用于处理某一事务。

## 模板能够帮助你理解想法

使用RemNote，能够帮助你就不同种类的知识建立模板。比如，我们能够建立关于站长的模板：

- 战争
  - 开始/结束时间
  - 战争各方
  - 结果/意义
- 第二次世界大战
  - 开始/结束时间：1939~1945

建立这些模板，你能明白需要学习什么，这使得学习相似类别的新概念更为容易。

我们通过相似的方式拆解并理解概念：

- 当我们学习历史事件时，我们显然需要知道事件的参与方，事件哪一年发生，以及事件带来了哪些影响。
- 当我们学习新菜谱时，我们需要知道这道菜需要什么食材，食材需要以什么顺序组合，以及烹饪各步骤需要多久。
- 当我们学习新单词，我们需要知道单词的词性（名词、动词还是形容词），以及单词应该在什么语境下使用。



- 功能
  - 概念
    - 战争与二战的关系是什么？战争是二战的父类。
  - Rem
    - 父类
    - 子类
  - 模板
    - 槽位：对概念的一项自动建议“描述”，是模板的子类。
      - **槽位案例**：战争-开始/结束日期
      - **目的**：帮助你通过简历模板组织观点，从而在将来更好的学习类似的概念。

## 通过创建[[标签]]使用模板

要使用已经存在的模板，只需要给Rem打上模板的tag。见以下视频：

## 建立自己的模板

使用这一功能，首先需要登录账号。

1. 点击此链接前往个人设定页-[![img](https://www.remnote.io/favicon.ico)RemNote](https://www.remnote.io/settings).

2. 在“高级编辑选项（Advanced Editor Options）”，打开“知识模板（templates for knowledge）”功能（父类，子类等。）

创建新模板仅需以下几步：

1. 创建一个[[概念]]以表示自己的模板，如”菜谱“

   - 菜谱

2. 向概念中添加槽位（如：食材）

   - 子Rem将被默认设置为”概念“，有两种方法将它改变成”槽位“

     1. 点击此Rem，在底栏设置为槽位。

     2. 点击Rem，输入”/slot“

   - 菜谱

     - 食材

3. 模板已经准备就绪！你可以输入#两次并搜索菜谱，以使用”菜谱“标签。这一标签将会出现在Rem文本的最右侧。

   - 外婆的曲奇菜谱
     - 食材：糖，鸡蛋

   以下是使用模板的工作流程。
