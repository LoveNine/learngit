## <center>谭志文的编码规范</center>

### 一、缩进与对齐
1-1.程序使用TAB缩进，TAB缩进空格数为4，对齐使用空格。  
1-2.大括号各占一行  
1-3.不同代码块之间必须空一行  
1-4.if,for,while等语句后必须加{}  
1-5.操作符前后要加空格，for语句和->操作符除外 

### 二、注释
2-1.文件注释必须列出：版权说明、文件名、作者、版本、创建日期、功能描述、历史版本，其中历史版本必须列出修改时间、修改人、版本号以及修改内容。  
示例：  
```
/*
 *   Copyright (C) 2017 TanZhiwen  All rights reserved.
 *   File Name :
 *   Author :
 *   Version :
 *   Create Date :
 *   Description :
 *   Heistory :
 */
```
2-2.函数注释必须列出：函数名、功能、输入参数、输出参数、返回值。  
示例：
```
/*
 * Function :
 * Description :
 * Input :
 * Output :
 * Return : 
 */
```
2-3.注释应放在其描述代码的上方或者右方（单条语句)。  
2-4.变量注释用//，与描述的代码间隔空格为4的倍数，一起定义的变量其注释要对齐。  
2-5.全局变量、宏定义等必须注释其含义及作用
### 三、命名原则
3-1.全局变量、常量全部用大写  
3-2.变量名风格要与所用系统的风格保持一致。

