01 CSS选择器

### 常用选择符
在CSS选择符中有两种，一种叫：ID选择符；一种叫：类选择符。
ID选择符的开头是以“#”
类选择符的开头是以“.” 

后代选择器：寻找特定元素或元素组的后代。后代选择器由其他连个选择器之间空格表示`h1 p`

伪类：用于向某些选择器添加特殊的效果
伪元素：用于将特殊的效果添加到某些选择器

> 伪类和伪元素的区别：1、伪类用：表示，伪元素用 ：：表示。2、伪类的效果可以通过添加一个实际的类来达到，而伪元素的效果则需要通过添加一个元素才能达到。所以一个称之为伪类，一个称之为伪元素

### 几种选择器

> 在对于站点功能或布局很重要的任何元素上，都应该避免使用这些高级选择器
通用选择器：作用像通配符，它匹配所有可用原色。它用※号表示。
后代选择器：
#### 高级选择器
1. 子选择器：只选择元素的直接后代，即子元素。但是对孙元素不起作用。`#ID>li`  用”\>”号表示
2. 相邻同胞选择器：一个元素对另个元素的相邻关系应用样式。简单的说就是，代码行的上一个元素对代码行的下一个元素，应用了样式。`#ID+P`然后单独ID下的“P”元素的样式会发生变化
3. 属性选择器：可以根据某个元素是否有某个属性来定义样式。例如：`acronym[title]`意思是：具有title属性的acronym元素应用于其他元素不同的样式。

#### 伪类和伪元素分类
常见的伪类：
- `:link` 
- `:visited`
- `:hover`
- `active`

常见的伪元素：
- ::first-letter
- ::first-line
- ::before
- ::after




