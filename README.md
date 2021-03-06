Django-Dynamic-Cabinet Maps
====

[![versions](https://img.shields.io/badge/python-2.7-yellow.svg)]()
[![versions](https://img.shields.io/badge/Development%20Status-0.1.dev2-orange.svg)]()
[![Documentation Status](https://readthedocs.org/projects/django-dynamic-cabinetmaps/badge/?version=v0.1.dev2)](http://django-dynamic-cabinetmaps.readthedocs.org/en/v0.1.dev2/?badge=v0.1.dev2)

一个轻量级、用于Django框架下的“动态生成机柜图”工具

> 目前还处于开发测试阶段，不够完善的地方，我会在文档中进行标注；欢迎大家提出宝贵意见。

>> 开发版本暂时不支持ie内核, Chrome\Firefox\Safair都支持

## Introduce

尽管绘制机柜图的需求是非常普遍的，尤其是在构建CMDB平台。但在其机柜设计与开发中，还是有不少的坑需要大家注意和解决；因此这个小项目或许可以多多少少解决大家在实际开发中遇到的痛点和麻烦。

对于机柜图的处理，先前已经有很多主流的做法，那么‘Django-Dynamic-Cabinet Maps’到底有什么优势呢？

- 轻量级

  - Don’t  XML / YML ！

  - Don’t  TinyXML ！
      
  - Don’t  Config Template !

  - Don’t  Repeat Yourself ！

- 动态性

  - 可动态调整机柜排版
  
  - 机柜的个数和机柜中导轨的个数可被不同的需求动态改变。

- 扩展性

  - 可定制的机柜编号

  - 可定制的机柜样式

  - 兼容和支持Bootstrap进行页面美化

  - 默认可支持100个机柜(通过定制可以更大0_0)
  

## Requirements

  - Python 2.7
  - Django 1.6, 1.7, 1.8
  - sass 3.4+ (不是必须)
  

## Installation

1. 通过pip进行安装

   ```
   pip install django-dynamic-cabinetmaps
   ``` 
   
   - 也可以使用GitHub直接clone进行安装

2. 在settings.py进行添加

   ```

    INSTALLED_APPS = (
        ......
    
        'cabinet_structure',
    
        ......
    )
   ```

## Demo

1. 从git上克隆 https://github.com/boylegu/django-dynamic-cabinetmaps.git

2. 然后进入``demoapp``

3. ``python manage.py runserver``

4. 通过浏览器访问``http://127.0.0.1:8000/cabinetmaps/``

  >> 目前demo是需要django 1.6运行


## Usage & Documentation

详细使用帮助,可以查看[文档](http://django-dynamic-cabinetmaps.readthedocs.org/en/latest/).

## Future

- 支持Python 3.
- 将会在正式版中修正样式显示的问题.
- 完善样式可定制的功能.
- 机柜编号可支持反转.
- 增加服务器数据渲染的API
- 支持机柜分页

## Support

  如果你有任何意见和交流可以直接通过GitHub或者加QQ讨论群:`315308272`与我交流
  

## Authors

  - 顾鲍尔 (Boyle Gu)







