# 软件需求（第3版）修正

<!-- @import " [TOC] " {cmd="toc" depthFrom=2 depthTo=6 orderedList=true} -->

<!-- code_chunk_output -->

1. [教材信息](#教材信息)
2. [关于本修正](#关于本修正)
3. [术语翻译修正](#术语翻译修正)
4. [章节翻译修正](#章节翻译修正)
    1. [第12章：一图胜千言](#第12章一图胜千言)
    2. [第13章：具体指定数据需求](#第13章具体指定数据需求)
    3. [第19章：需求开发之外](#第19章需求开发之外)
    4. [第20章：敏捷项目](#第20章敏捷项目)
    5. [第21章：改进型和替换型项目](#第21章改进型和替换型项目)
    6. [第22章：软件包方案项目](#第22章软件包方案项目)
    7. [第23章：外包项目](#第23章外包项目)
    8. [第24章：业务过程自动化项目](#第24章业务过程自动化项目)
    9. [第25章：业务分析项目](#第25章业务分析项目)
    10. [第26章：嵌入式和其他实时系统项目](#第26章嵌入式和其他实时系统项目)
5. [附录翻译修正](#附录翻译修正)
    1. [附录C：范例需求文档](#附录c范例需求文档)

<!-- /code_chunk_output -->

## 教材信息

|信息名|信息值|
|--|--|
|原名|Software Requirements, third edition|
|译名|软件需求（第3版）|
|出版社|清华大学出版社|
|ISBN|978-7-302-42682-0|
|原著|Karl Wiegers, Joy Beatty|
|译者|李忠利，李淳，霍金健，孔晨辉|

## 关于本修正

1. 本修正暂只包含可能影响理解英文原版原意的翻译，并不包含英文原版的修正，也不包含不符合中文语法或中文使用习惯但不太影响理解英文原意那部分（该部分实在太多，如果全部修正，估计得重新翻译）
1. 本修正非官方修正，仅是由于本人教学过程中觉得有必要为学生提供参考，以免影响教材的使用
1. 本人水平极有限，期待对本人的修正进行修正、或补充本人的遗漏

## 术语翻译修正

1. User Class
    1. 教材翻译：用户类别、用户群
    1. 修正翻译：用户群体
    1. 修正说明：教材时而翻译成“用户类别”、时而翻译成“用户群”，**可能** 翻译成“用户群体”更恰当
1. Acceptance Criteria
    1. 教材翻译：验收条件、验收标准
    1. 修正翻译：验收标准
    1. 修正说明：教材时而翻译成“验收条件”、时而翻译成“验收标准”，按约定俗成，翻译成“验收标准”较为恰当，因此，应统一翻译成“验收标准”
1. Business Process
    1. 教材翻译：业务过程
    1. 修正翻译：业务流程
    1. 修正说明：Process在不同的术语中约定俗成翻译成“过程”、“流程”或“进程”，如“软件过程”、“业务流程”和“进程控制”，而“业务流程”是主流的翻译

## 章节翻译修正

### 第12章：一图胜千言

1. P200表12-2第1行内容第1段：~~项目环境图~~ ==> ==关联图/关系图/环境图（context diagram）==
1. P200表12-2第1行内容第2段： ~~生态关系图~~ ==> ==生态系统图==
1. P200表12-2第2行内容：~~业务过程图~~ ==> ==业务过程==
1. P200表12-2第3行内容：类图表述 ~~对象类和类对象数据间的逻辑关系~~ ==> ==对象类（及其数据）间的逻辑关系==
1. P210第1段： 对话图与 ~~流图~~ 看起来有些相似 ==> ==流程图（flowcharts）== （后续的“流图”均应为“流程图”）

### 第13章：具体指定数据需求

1. P218标题： ~~具体~~ 指定数据需求 ==> ==明确==
1. P218第4段： 一个好的着手点是 ~~系统背景图~~ 中的输入/输出流 ==> ==系统环境图（system context diagram）==

### 第19章：需求开发之外

1. P325正文01段04行
    1. 英文原文：Some of these activities are the business analyst’s responsibility,whereas others fall within the project manager’s domain
    1. 教材翻译：这些工作中，有一些是业务分析师的职责，而其他的则落在~~产品经理~~的头上
    1. 修正翻译：这些工作中，有一些是业务分析师的职责，而其他的则落在==项目经理==的头上
1. P326正文倒数01段01行
    1. 英文原文：Requirements engineering activity is distributed throughout the project in different ways, depending on whether the project is following a sequential (waterfall), iterative, or incremental development life cycle
    1. 教材翻译：需求工程工作以不同的方式遍布于项目之中，取决于项目遵循的开发~~声明~~周期是串行式的（瀑布）、迭代式的还是增量式的
    1. 修正翻译：需求工程工作以不同的方式遍布于项目之中，取决于项目遵循的开发==生命==周期是串行式的（瀑布）、迭代式的还是增量式的
1. P332正文05段01行
    1. 英文原文：Reasonably stable requirements, at least for the forthcoming development iteration
    1. 教材翻译：~~相当~~稳定的需求，至少对即将开始的开发迭代~~如此~~
    1. 修正翻译：==足够==稳定的需求，至少对即将开始的开发迭代==周期来说是足够的==

### 第20章：敏捷项目

1. P342正文02段02行
    1. 英文原文：In general, though, on waterfall development projects the team puts considerable effort into trying to get the full requirements set “right” early on.
    1. 教材翻译：为了~~尽量~~使整个需求集合~~合~~“正确”，团队会投入大量的精力
    1. 修正翻译：为了==尽早==使整个需求集合“正确”，团队会投入大量的精力
1. P344正文03段01行
    1. 英文原文：The product backlog on an agile project contains a list of requests for work that the team might perform
    1. 教材翻译：敏捷项目中的产品Backlog包含团队采取行动的~~请求~~清单
    1. 修正翻译：敏捷项目中的产品Backlog包含团队可能要采取行动的需求清单列表
1. P344标题03
    1. 英文原文：Timing
    1. 教材翻译：~~确定时机~~
    1. 修正翻译：时间控制
1. P346标题“期待变更”下的正文01段01行
    1. 英文原文：The biggest adaptation that BAs need to make when a requirement change arises on an agile project is to say not, “Wait, that’s out of scope” or “We need to go through a formal process to incorporate that change,” but rather, “Okay, let’s talk about the change
    1. 教材翻译：在敏捷项目中，需求发生变化时，业务分析师要做的最大调整是~~学会拒绝~~：“等等，这不在范围之内”或者“我们需要走正式流程来加入这个变更”，而~~不~~是说“好吧，我们来谈一谈这个变更”
    1. 修正翻译：在敏捷项目中，需求发生变化时，业务分析师要做的最大调整是==态度转变==：==从说==“等等，这超出范围了”或“我们需要走正式流程才能加入这个变更”，==变成“好的，我们一起聊聊这个变更”==
1. P347正文01段01行
    1. 英文原文：Most of the practices described throughout this book can easily be adapted to agile projects, perhaps by altering the timing when they’re used, the degree to which they are applied, or who performs each practice
    1. 教材翻译：整本书介绍的大多数实践通过改变使用时机、应用的程度或者开展每个实践的人，~~或许可以轻松适应于敏捷项目中~~
    1. 修正翻译：整本书介绍的大多数实践==可以轻松地适用于敏捷项目中==，例如，通过改变使用的时机、==调整应用的深度==或者==改变或调整执行这些实践的人==

### 第21章：改进型和替换型项目

1. P349案例标题
    1. 英文原文：The Case of The Missing SPEC
    1. 教材翻译：{++缺少规范++}
    1. 修正翻译：规格说明缺失的案例
1. P350正文02段01行
    1. 英文原文：The changes made could degrade the performance to which users are accustomed
    1. 教材翻译：所做改变可能使用户{++已经习惯的性能降低++}
    1. 修正翻译：所做改变可能使用户==原本习惯的系统的性能降低==
1. P353标题“找不到原有需求怎么办”下的正文01段01行
    1. 英文原文：In the absence of reliable documentation, teams might reverse-engineer an understanding of what the system does from the user interfaces, code, and database
    1. 教材翻译：在没有可靠文档的情况下，团队{++要了解++}系统的情况，就要对用户界面、代码和数据库进行{++反向++}工程
    1. 修正翻译：在没有可靠文档的情况下，团队==如果想了解==系统的情况，就需要对用户界面、代码和数据库进行==逆向==工程
1. P355标题“如何发现现有系统的需求”下的正文01段01行
    1. 英文原文：In enhancement and replacement projects, even if you don’t have existing documentation, you do have a system to work from to discover the relevant requirements
    1. 教材翻译：在改进型项目和替换型项目中，{++无论有无++}现成文档，{++都要从系统中发现相关需求++}
    1. 修正翻译：在改进型项目和替换型项目中，==即使没有==现成文档，==也需要一套用于发现相关需求的工作机制==

### 第22章：软件包方案项目

1. P362标题“评估方案”下的04段02行
    1. 英文原文：You can find the information to make this assessment from product literature, a vendor’s response to a request for proposal (RFP), or direct examination of the product
    1. 教材翻译：可以从产品资料、厂商发出的 ~~应标标书（RFP）~~ 或者直接查验产品获得评估所需要的信息
    1. 修正翻译：可以从产品资料、厂商发出的 ==应标书（response to a Request For Proposal）== 或者直接查验产品获得评估所需要的信息
    1. 修正说明：教材翻译容易令人误以为“应标书”对应的英文术语缩写是“RFP”

### 第23章：外包项目

1. P371标题“验收标准”下01段01行
    1. 英文原文：begin with the end in mind
    1. 教材翻译：~~以始为终~~
    1. 修正翻译：==以终为始==

### 第24章：业务过程自动化项目

1. 整章
    1. 英文原文：business process
    1. 教材翻译：业务~~过程~~
    1. 修正翻译：业务==流程==
    1. 修正说明：business process主流的术语翻译为“业务流程”

### 第25章：业务分析项目

1. P379图25-1图题
    1. 英文原文：The components of a simple business analytics framework
    1. 教材翻译：简单业务分析框架的构成
    1. 修正翻译：业务分析系统的一个简要框架构成组件
    1. 修正说明：原翻译容易令人误以为“简单业务分析系统的框架构成”

### 第26章：嵌入式和其他实时系统项目

1. P395标题“有时限的需求”
    1. 英文原文：Timing Requirements
    1. 教材翻译：~~有时限~~的需求
    1. 修正翻译：==时序==需求
1. P395正文01段01行
    1. 英文原文：Timing Requirements
    1. 教材翻译：~~定时~~需求
    1. 修正翻译：==时序==需求

## 附录翻译修正

### 附录C：范例需求文档

1. P523图C-4：订餐订单的状态转化图的状态“已取消”（ **状态转换箭头标签为“自助餐厅准备食物”的“已取消”** ）
    1. 英文原文：Prepared
    1. 教材翻译：~~“已取消”~~
    1. 修正翻译：==“已备餐”==
1. P523图C-4：订餐订单的状态转化图的状态“已备餐”
    1. 英文原文：Pending Delivery
    1. 教材翻译：~~“已备餐”~~
    1. 修正翻译：==“待送餐”==
1. P523图C-4：订餐订单的状态转化图的状态“等待送餐”
    1. 英文原文：Delivered
    1. 教材翻译：~~“等待送餐”~~
    1. 修正翻译：==“已送餐”==
