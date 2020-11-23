# TIEreimple
code reviewers recommendation 

## 收集数据
.....
## 方法
1. 文本贝叶斯分类器，每一类是一个code reviewer D。利用term的词频 + 链式法则计算被review被Di分配的概率。（公式1，2）
2. path相似度，一个review的路径和M天之内的historical reviews的相似度，利用两个路径中的公共子路径比率+求和表示。（公式3）
3. 正则化 1. 和 2. 的相似度，加权计算。（公式5）

## reference

Who Should Review This Change?

## other works

 Who should review my code

它有约145个引用次数

 Modern code review: a case study at google ICSE-SEIP2020 
 Multi-objective code reviewer recommendations: balancing expertise, availability and collaborations 2020 ASE
 Code Review Knowledge Perception: Fusing Multi-Features for Salient-Class Location TSE 2020
 RSTrace+: Reviewer suggestion using software artifact traceability graphs Information and Software Technology 2020
