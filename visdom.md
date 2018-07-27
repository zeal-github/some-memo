# 一些使用visdom的坑

## 1.远端使用visdom的时候

+ 1、在创建环境的时候：viz = visdom.Visdom(port= ?) 如果不是使用默认端口8097，则需要传入一个端口号
+ 2、远程启动visdom的时候：python -m visdom.server -p port_number
+ 3、如果是让服务器的端口号重定向到本地端口号，则在本地`~/.ssh/config`文件下加入下面的语句;不过这个时候最好也是指定端口号
  
``` 
LocalForward 127.0.0.1:8097 127.0.0.1:8097
```
