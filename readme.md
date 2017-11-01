# Django 使用 FusionCharts 创建图表

把 django-wrapper-master.zip 做为应用集成到 Django 中，代码见 django-wrapper-master 分支。

注意：django-wrapper-master.zip 中有些代码混用了 tab 和空格导致启动异常，我在 ide 中做了修复，另一个是模块导入书写方式错误做了调整。

## 相关资料

- Django Framework – [Download Link](https://www.djangoproject.com/download/)
- FusionCharts Library – [Download Link](https://www.fusioncharts.com/download/)
- FusionCharts Django wrapper – [Download Link](https://www.fusioncharts.com/django-charts/)

- 参考： [How To Create Charts In Django](https://www.fusioncharts.com/blog/creating-charts-in-django/)


## 演示方法
    git clone https://github.com/wangwanzhong/wwz_dj_fusioncharts.git
    cd wwz_dj_fusioncharts
    /opt/py352/bin/pyvenv env
    source env/bin/activate
    pip install -r requirements.txt
    python manage.py runserver

打开浏览器访问 http://localhost:8000/


## 接下来
登录官网址查看更多演示例子 https://www.fusioncharts.com/

