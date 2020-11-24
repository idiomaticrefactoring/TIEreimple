# TIEreimple
code reviewers recommendation 

## 收集数据
从[1]
## 方法
1. 文本贝叶斯分类器，每一类是一个code reviewer D。利用term的词频 + 链式法则计算被review被Di分配的概率。（公式1，2）
2. path相似度，一个review的路径和M天之内的historical reviews的相似度，利用两个路径中的公共子路径比率+求和表示。（公式3）
3. 正则化 1. 和 2. 的相似度，加权计算。（公式5）

## reference

Who Should Review This Change?

## other works

[1] Who should review my code (Patanamon Thongtanunam Saner2015)

它有约145个引用次数

 Modern code review: a case study at google ICSE-SEIP2020 
 
Vladimir Kovalenko; Nava Tintarev; Evgeny Pasynkov; Christian Bird---Does Reviewer Recommendation Help Developers TSE 2020 
 
 Soumaya Rebai, Abderrahmen Amich, Somayeh Molaei, Marouane Kessentini---Multi-objective code reviewer recommendations: balancing expertise, availability and collaborations 2020 ASE
 
 Yuan Huang; Nan Jia; Xiangping Chen; Kai Hong; Zibin Zheng --- Code Review Knowledge Perception: Fusing Multi-Features for Salient-Class Location TSE 2020
 
 RSTrace+: Reviewer suggestion using software artifact traceability graphs Information and Software Technology 2020
 
 Patanamon Thongtanunam, Shane McIntosh, Ahmed E. Hassan, --- Revisiting code ownership and its relationship with software quality in the scope of modern code review  ICSE 2016
 
 M. M. Rahman, C. K. Roy, J. Redl, and J. A. Collins ---- Correct: Code reviewer recommendation at github for vendasta technologies ASE 2016

 Motahareh Bahrami Zanjani; Huzefa Kagdi; Christian Bird --- Automatically Recommending Peer Reviewers in Modern Code Review.  TSE 2016
 
 Y. Yu, H. Wang, G. Yin, and T. Wang ---- Reviewer recommendation for pull-requests in github: What can we learn from code review and bug assignment? Information and Software Technology 2016
 
 V. Balachandran----Reducing human effort and improving quality in peer code reviews using automatic static analysis and reviewer recommendation. ICSE 2013
 

