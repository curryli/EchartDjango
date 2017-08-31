# EchartDjango
基于django和Echart的可视化方案
import django  要是报错的需要先pip install django

去echart官网下载相应的js文件，放在static文件夹下

打卡pycharm，（用pycharm新建python工程以后，要想把现有的src目录下的文件添加到工程，直接把该src文件夹复制到工程根目录下即可）

要是直接运行manage.py程序的话 会提示一大堆东西，那无非是提示没有传入参数。所以在pycharm上传入参数运行即可：操作方式如下
打开manage.py文件 在pycharm右上角点击edit configurations 编辑配置参数

详细运行方法见
http://www.cnblogs.com/qinjiting/p/4678893.html

右键运行manager.py

由于我们在url文件里面指定了一个    portal/  端口，所以我们在浏览器上打开http://0.0.0.0:8000/portal  即可显示.



