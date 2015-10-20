# 张逸霄的自我介绍
## Qpython
我现在觉得Qpython是一个很好用的App.
如果你要很好地使用它，你需要：
* 一部Android手机
* 一个蓝牙键盘
* 一颗充满热情的心

*** 

## 关于自己最近的学习现状
* Python属于囫囵吞枣阶段，现在看到了循环和判断。当然之后还打算看一遍，因为实在是知识浅薄。
* 一直停留在指针那里没时间去看（真是遗憾）

> 知之为知之，不知为不知，是知也。

*** 

## 代码实例

    import math
    def main():
        print("This is a grogram designed to get the solution to qurladratic.")
        a, b, c =eval(input("Please enter the coeffidents: a, b, c "))
        delta= b * b - 4 * a * c
        if delta>= 0:
            if a != 0:
                discroot = math.sqrt(delta)
                root1 = ( - b + discroot ) / ( 2 * a )
                root2 = ( - b - discroot ) / ( 2 * a )
                print("Solution: " , root1 , root2 )
            else:
                root = ( - c / b )
                print ( "Solution: " , root )
        else:
            print("There is no solution.")

    main()

***

## What's More? 

* 强烈推荐大家去做MBTI心理测试，很实用的测试。
