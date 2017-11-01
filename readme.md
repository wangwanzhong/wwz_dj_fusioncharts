# Django 使用 FusionCharts 创建图表

当前所处分支 django-wrapper-master，演示了更多官方提供例子。

注意：官方下载的 django-wrapper-master.zip 中有些代码混用了 tab 和空格导致启动异常，另一个是模块导入书写方式错误，我在 ide 中格式化做了修复。

## 相关资料

- [FusionCharts 官网地址](https://www.fusioncharts.com/)
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
