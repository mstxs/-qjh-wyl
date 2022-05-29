# 编译原理大作业
## Miroc

### 5.29新增 `wyl`：
* Absyn.fs—— 抽象语法树文件
    * 定义基础类型：TypString，TypeFloat，TypeVoid
    * 定义了基础表达式：常数Float值
    * 定义了for声明
* Clex.fsl—— 词法分析器
    * for -> FOR 
    * string -> STRING 
* CPar.fsy—— 语法分析器
    * ConstString
    * ConstFloat
    * ConstChar 