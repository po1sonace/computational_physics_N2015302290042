# **Exercise_03**
 
## 数值求解微分方程的思路
  课上学习了欧勒法求解微分方程的基本方法。这种方法思路明白易懂，但也存在一些问题。比如程序过程较为繁琐，迭代过程易出错，而且难以求解高阶微分方程
。在课下，我了解了scipy函数库中的obeint函数可以广泛应用于常微分方程的求解。
## 准备工作
  从 anaconda中导入scipy函数库以及matplotlib工具包
## 编写程序与调整
  应用 obeint可以直接定义微分方程的形式的优点，便捷写出程序。基本框架写出后，根据题目给出的；两种情况做出不同的初始值以及方程的形式。同时调整
步长 以确保精度。最后对曲线的输出进行调整，调整其y轴与x轴的单位，使其自然清晰。加入标题及坐标轴说明。
## 运行结果
  题目的第一种情况 定初始人数为100 a=10 b=3 
  ！[image](https://github.com/Liowen0918/computational_physics_N2015302290042/blob/master/case1.png)
  
  
  题目的第二种情况 定初始人数为10000 a=10 b=0.01
  ！[image](https://github.com/Liowen0918/computational_physics_N2015302290042/blob/master/case2.png)
 
## 代码
https://github.com/Liowen0918/computational_physics_N2015302290042/blob/master/exercise_03_code.md
