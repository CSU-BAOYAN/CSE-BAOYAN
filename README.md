# 保研攻略

![Read the Docs](https://img.shields.io/readthedocs/postgraduate-recommendation?style=flat-square)

地址：[https://cse-baoyan.readthedocs.io/zh/latest/](https://cse-baoyan.readthedocs.io/zh/latest/)

由中南软工学长学姐编写的保研攻略，希望大家都能更快更高效更少踩坑地成功保研，拥有光明的未来。
目前正在收集2020级保研经验贴，欢迎大家 Star & Fork 帮助学弟学妹们！

# TODO
1. 通用建议和文书准备

# 贡献

## 构建

1. Fork本项目
2. Clone到本地
3. 安装环境
```shell
conda create --name baoyan
conda activate baoyan
pip install sphinx restructuredtext-lint sphinx_rtd_theme
```
4. 修改项目
5. 生成html文件：工程目录下执行：`make clean && make html`
6. 使用浏览器打开`build/html/index.html`，即可预览已经产生的文档！


本项目使用[reStructuredText](http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html)进行写作，新版的Python文档就是由Sphinx生成的，并且它已成为Python项目首选的文档工具，语法和MarkDown差不多，用到什么语法[点击这里](https://rst-tutorial.readthedocs.io/zh/latest/index.html)查就可以。


本项目使用[sphinx](http://www.sphinx-doc.org/en/master/contents.html)进行文档生成，如果需要学习对项目进行修改，请查看sphinx的文档，或者[这个教程](https://zhulao.gitee.io/blog/2019/04/30/Sphinx-ReStructuredText%E5%88%B6%E4%BD%9C%E6%89%8B%E5%86%8C%E6%96%87%E6%A1%A3/index.html)。

## Tips

- 插入本地图片可用如下语法：
    - `.. image:: ../../../static/test.png`
- 设定锚点内连接语法：
    - .. _anchor:
    - `使用锚点<anchor>`

## 贡献

您可以用如下两种方式对此项目进行贡献：

- fork项目之后发PR
- 联系**雨夜闭门** ([GitHub](https://github.com/rainyNighti))获取本项目写权限后，往本项目中**非master**分支提交您的内容，再发PR

在文档中手工维护，若您是第一次贡献本项目，并希望将自己的个人信息写在文档中，请进行以下步骤（**若您不想加入，则可以什么都不做**）：

- 在`sources/authors.rst`中，根据已有的格式加入您的个人信息


# 许可证

本项目所有文本内容在[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)下授权。

