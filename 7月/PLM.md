# *PLM* 

### 一、物料库和产品库
> 1.1 共同点是物料库和产品库都可以查看我们的BOM

> 1.2 不同点是物料库包含有产品的成品、半成品、及所有的原料、结构件和线束,产品库包含所有产品的成品。

>> 产品库分为工作区、归档区、发布区。
>>> 工作区放置了新生成或升级版本并且未归档的成品

>>> 归档区存放了归档状态的产品

>>> 发布区存放了经流程发布过的成品

> 1.3 查看物料信息

> 属性-》组成

### 二、BOM制作

> 步骤1
>> 在物料库（半成品）和产品库（成品）中查找到该项目的相应物料

>步骤2
>>在父层物料“组成”栏添加子层物料

>>引用-》物料-》搜索-》添加

>步骤3
>>子层物料的复制

>>产品库->归档区->通用平台产品->复制-》成品的“组成”界面-》粘贴

>步骤4
>>勾上BMS成品BOM-》点击启动流程按钮（将BOM成品进行审批、归档和发布）

>特殊方法
>>步骤2是引用EXCEL文档，其余步骤一样

### 三、BOM变更

>1.工作台”—“我的变更”—“DCN\ECN管理

>2.新建-》业务类型-》DCN-》确定

>3.填上主题->确定->确定

>4.变更类型--》设计变更-》确定

>5.变更对象->(如果是修改BMS成品下层的子物料就选择“添加产品”方便查找，如果是修改成品下面的某个半成品的子物料就选择“添加物料”—“直接选择”。)

>6.择查询条件->查不到试下变更“归档版本”为“发布版本”

>7.弹出页面显示反查你选择的半成品将影响到的上层物料，不用管，点确定。(这一步请注意，如果是修改通用平台BOM则跳过此步直接点页面下方的启动，若修改单个项目BOM则必须执行此步。！)