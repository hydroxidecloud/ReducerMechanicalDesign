# 用于《机械设计课程设计》中的减速箱设计的计算

## Requirement
- `Python 3+` 
## 1. Overview
几乎所有高校的机械类专业都有《机械设计课程设计》课程，课程内容几乎都是设计一个减速箱。可能是一级减速，二级减速等，可能是直齿齿轮减速，斜齿轮减速等。在进行课程设计时，齿轮、带传递、蜗轮蜗杆等传动部件的计算量庞大，而且极容易出错。有的同学可能是手按计算器，一步一步来，这样效率是极低的。为了提高计算效率以及优化设计，我在进行课设的时候，借助了Python语言计算。

参考源Github链接：https://github.com/HuimingPan/course-exercise-in-mechanical-design


## 2. Structure
- caculation.py 是主程序；
- belt.py 带传动计算；
- coupling.py 滚动轴承计算；
- gear.py 齿轮传动计算；
- key.py 键连接计算；
- load_anlysis.py 轴上载荷计算；
- rolling_bearing.py 滚动轴承计算；
- shaft.py 轴直径的初步计算；
## 3. Deficiency
由于是在进行课设的时候写的程序，时间仓促，有很多不足待改进，也有很多想法没有能够实现。如果大家看到了这篇，希望能够一起来改进这个程序。
- 没有建立《课程设计》中涉及的国标数据库，在调用的时候，需要手动查表并输入；
- 没有建立AutoCAD的接口，使自动绘图；
- 不能进行优化设计；
- 没有引入机械动力学计算；
