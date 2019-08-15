# yml部署模板使用方法

该模板主要解决初始化服务器没有安装docker,docker-compose等工具等情况下一键部署yml文件。

使用方法：

1、git clone https://github.com/luckman666/deployYmlDemo.git

2、将已经编辑好的yml文件放在.sh同目录位置。例如例子上面我们要部署mysql.yml。原则上建议要部署什么就yml就起什么名字。

3、编辑base.config内容。

4、付权限并执行./mysql.sh。

全程不用修改.sh文件，只需要修改base.conf和放入你要部署yml即可
可以使用docker-compose -f ./*.yml ps 查看执行结果

欢迎大家关注我个人的订阅号，会定期分享学习心得，相关案例信息!
![index1](https://github.com/luckman666/devops_kkit/blob/master/gzh.jpg)
