# 
# 说明

>  基于Python + Flask + PyEcharts +plotly实现的数据可视化平台，并包含数据分析基本图表的绘制。

基于Python + Flask + PyEcharts +plotly的自动数据可视化平台。 

> 该项目有三个目的：
> 1.指导数据分析初学者学习基本的pyecharts绘图，并展示到Flask开发的web平台上。 
> 
> 2.根据数据的变量类型和逻辑，指导数据分析初学者绘制该数据对应的图（如单定量-直方图） 
> 
> 3.根据用户上传数据变量的性质，单变量还是双变量，定性变量还是定量变量，自动进行数据可视化。
> 
> it is a data visualization platform based on Python + flask + pyechards + plot, and includes the drawing of basic charts for data analysis.



1. Automatically visualize data according to the nature of data variable, whether it is single variable or double variable, qualitative variable or quantitative variable.



2. Among single variables, qualitative single variables include column chart, pie chart and rose chart, and quantitative single variables include histogram. In multivariable, qualitative and quantitative variables draw box line diagram, quantitative and quantitative scatter diagram, area diagram and broken line diagram of quantitative and time variables.



3. Purpose: it is used to guide beginners of data analysis to learn basic pyechards drawing and display it on the web platform developed by flask.

# 依赖库
| Dependency | Version |
| ------ |------|
| Python | 3.8.8 |
| flask | 1.1.1 |
| pyecharts | 1.7.1 |
| requests | 2.22 |


# 使用
```
python run.py
# 在浏览器中访问http://localhost:776
```
# 前端展示

![image-20211226213439459](img/image-20211226213439459.png)

![image-20211226213809900](img/image-20211226213809900.png)

定性单变量的柱形图、饼图、玫瑰图，定量变量的直方图和面积图。

![image-20211226213823503](img/image-20211226213823503.png)

多变量定性和定量变量的箱线图，定量和定量的散点图，定性和定性变量的折线图。用于指导数据分析初学者学习基本的pyecharts绘图，并展示到Flask开发的web平台上。

![image-20211226213535442](img/image-20211226213535442.png)

![image-20211226213555179](img/image-20211226213555179.png)

![image-20211226213609398](img/image-20211226213609398.png)

![image-20211226213629502](img/image-20211226213629502.png)

![image-20211226213649876](img/image-20211226213649876.png)

![image-20211226213707403](img/image-20211226213707403.png)

![image-20211226213745083](img/image-20211226213745083.png)

参考的网站博客:

pyecharts 中文文档

https://gallery.pyecharts.org/#/Candlestick/professional_kline_chart
