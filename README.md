# 12306_train_checkticket
A python-based train ticket query script(object to 12306)


要使用火车票查询脚本，需要把前三个脚本都下载。

查询格式如下：

 -d           动车
 -g           高铁                                                                                               
 -k           快速
 -t           特快    
 -z           直达

输入    python3 checkticket.py -d 上海 北京 2017-07-30

其中多选格式为   -dg  或者 -dgk    （不写则默认所有的火车型号）

输入（上海）前一个地点为出发站    输入（北京）后一个地点为到达站 

日期格式为  xxxx-xx-xx


url失效怎么办？


在12306中Network中，query开头的便是最新的url。把checkticket.py中的url替换掉就可以了
