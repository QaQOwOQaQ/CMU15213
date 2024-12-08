# CMU15-213 Lab Record

## How to get grade?
### 1. data lab
``` shell
make clean
make btest
./btest
```

### 2. bomb lab
[reference](https://blackdragonf.github.io/2017/04/18/%E6%B7%B1%E5%85%A5%E7%90%86%E8%A7%A3%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%B3%BB%E7%BB%9FBombLab%E5%AE%9E%E9%AA%8C%E6%8A%A5%E5%91%8A/)
通过 `./bomb` 运行程序，输入六个字符串拆掉六个炸弹(phase1~phase6)
当且仅当phase_6解除并且从phase_4的输入字符串依次读取两个数字和一个字符串且这个字符串为”DrEvil”时，可以进入第七个隐藏炸弹。

### 3. attack lab
[reference](https://earthaa.github.io/2020/02/11/CSAPP-Attacklab/)
首先,我在 attack_lab 下添加了两个文件
* makefile 
* reference_ans 

然后,该实验共有5个phase,对于phase1,将答案放在ans/ans1.txt中,
然后回到attack_lab目录下运行make test1,其余四个也是同理



### 5. cache lab
[reference](https://lrl52.top/772/csapp-labcache-lab/)
``` shell
make clean
make
./test-csim
python2 ./driver.py
```

### 6. performance lab
已经被 cache lab 取代了
``` shell
make clean
make
./driver
```


### 7. shell lab
[reference](https://lrl52.top/784/csapp-labshell-lab/)
[reference](https://zhuanlan.zhihu.com/p/492645370)
查看 `makefile`
通过运行自己的shell与reference shell
对比结果来测试程序

### 8. malloc lab
[reference](https://doraemonzzz.com/2021/09/15/2021-9-15-CMU-15-213-Lab6-Malloc-Lab/)
[tracefiles](https://github.com/quanvuong/CSAPP-Malloc-Lab)
``` shell
make clean
make
./mdriver
```


### 9. proxy lab
[reference](https://www.yalexin.top/blog/blog/135)
[reference](https://lrl52.top/826/csapp-labproxy-lab/)

``` shell
make clean
make
./driver.sh
```

