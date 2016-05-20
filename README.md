# Homework-9
#单摆的混沌现象
##摘要
主要讨论了有耗散和外加驱动力情况下单摆的运动情况，单摆会出现混沌现象，给出了在不同初始条件下的运动情况，了解混沌现象。
##正文
体系的微分方程由下式给出  
![](https://github.com/Wangzhengwhu/Homework-9/blob/master/%E5%85%AC%E5%BC%8F1.png)  

其中右式第一项为重力的影响，第二项为耗散项，第三项为周期性驱动力，混沌现象主要由第三项体现出来。我们利用利用euler_cromer方法在
适当的初始条件下给出数值解。[程序1](https://github.com/Wangzhengwhu/Homework-9/blob/master/%E7%A8%8B%E5%BA%8F1.py)  

![](https://github.com/Wangzhengwhu/Homework-9/blob/master/1.png)  


其中左图显示了在不同的周期性驱动力作用下，转角随时间变化的图像。  
右图显示了不同的周期性驱动力作用下，角速度随时间变化的关系图像。  
显示了混沌摆在不同驱动力下转角和角速度的模拟图。  


[程序2](https://github.com/Wangzhengwhu/Homework-9/blob/master/%E7%A8%8B%E5%BA%8F2.py)  
![](https://github.com/Wangzhengwhu/Homework-9/blob/master/2.png)  

其中左图显示了在不同大小的耗散力下，转角随时间变化的图像。  
右图显示了不同大小的耗散力下，角速度随时间变化的关系图像。  
从上面2幅图中可以看出，混沌与周期性驱动力的大小，耗散力都有关，当驱动力越大时，越容易出现混沌现象，耗散力越小时，也越容易出现混沌现象。  
![](https://github.com/Wangzhengwhu/Homework-9/blob/master/5.png)  
![](https://github.com/Wangzhengwhu/Homework-9/blob/master/6.png)  
以上2图显示了在初始的角度相差0.001°的情形下，角速度随时间的变化，其中第一幅图的FD=1.2，第二幅为0.5。说明了在不同大小的驱动力下，周期性变化巨大。  

[程序3](https://github.com/Wangzhengwhu/Homework-9/blob/master/%E7%A8%8B%E5%BA%8F3.py)  
![](https://github.com/Wangzhengwhu/Homework-9/blob/master/4.png)  
上图显示了在驱动力为0.5时没有出现混沌现象，为1.2时出现混沌现象。  

##结论
混沌想象的出现与外加驱动力的周期，振幅都有关系，还与耗散大小相关，在初始值相差很小的情况下，经过一段时间会出现截然相反的情况。

##致谢
感谢刘星辰同学提供的程序


