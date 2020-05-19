<!--
 * @Author: zx
 * @Date: 2020-05-19 21:40:10
 * @LastEditors: zx
 * @LastEditTime: 2020-05-19 23:06:14
 * @Description: 使用环境:
VS Code + 两个插件: yzhang.markdown-all-in-one + shd101wyy.markdown-preview-enhanced + Chrome
输出选用Chrome. 若输出有问题 请更改此项设置 markdown-preview-enhanced.chromePath
安利文件头/函数注释生成插件: obkoro1.korofileheader
 * @FilePath: \Markdown\UESTC_Experiment_Report_Markdown_Template.md
--> 
<!-- 首页 做的不是特别好x 若需要则取消注释 -->
<!-- <!--  -->
<br>
<font size=8 face="华文行楷"><center>电子科技大学<u>自动化工程</u>学院</center></font> 
<br><br><br><br> 
<br><br><br><br>
<br><br><br>
<font size=20 face="楷体"><center><b>实验报告</b></center></font>
<br><br><br>
<br><br><br>
<br><br>
<b>
<font face="宋体" size=4>
<center>
&ensp; &ensp; &ensp; &ensp;&ensp;&ensp;
学 &ensp;&ensp;&ensp;号  
<u>
&ensp;&ensp;&ensp;&ensp;
2020051821414
&ensp;&ensp;&ensp;&ensp;
</u>
<br>
&ensp; &ensp; &ensp; &ensp;&ensp;&ensp;
姓 &ensp;&ensp;&ensp;名
<u>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;
XXX
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;
</u>
<br>
&ensp;&ensp;（实验）课程名称
<u>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;
XXX
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;
</u>

<br>
&ensp; &ensp; &ensp; &ensp;&ensp;&ensp;
理论老师
<u>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;
XXX
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;
</u>
<br>
&ensp; &ensp; &ensp; &ensp;&ensp;&ensp;
实验老师
<u>
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;
XXX
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp; &ensp;
</u>
</center>
</font>
</b>
<div STYLE="page-break-after: always;"></div>


<font size=22 face="方正舒体"><center>电子科技大学</center></font>
<font size=26><center>**实 &ensp; 验 &ensp; 报 &ensp; 告**</center></font>

<font face="宋体" size=4>
<b>
<!--文件头 第一行 需要改动!!!!!!!!-->
<div>
    <span style="float: left">学生姓名: name</span>
    <span style="float: right">指导老师: t_name</span>
</div>
<center>学号: 2020051821414 </center>
<!--文件头 第二行 需要改动!!!!!!!!-->
<div>
    <span style="float: left">实验地点: N/A</span>
    <span style="float: right">实验时间: 2020/05/18</span>
</div>
<br>

#### 一、实验室名称: 

#### 二、实验项目名称: 

#### 三、实验学时：

#### 四、实验原理：

#### 五、实验目的：

#### 六、实验内容：

#### 七、实验器材（设备、元器件）：

#### 八、实验步骤：

#### 九、实验数据及结果分析：

#### 十、实验结论：

#### 十一、总结及心得体会：

#### 十二、对本实验过程及方法、手段的改进建议：
</b>
</font>

<!-- 注释 -->
<!-- 
P.S. 一些格式
---

普通字体  
**加粗字体**  
__加粗字体__  
~~划掉的字体~~  
_斜的字体_  
<font face="方正舒体">更换字体</font>  
<font size=8 face="方正舒体">更换变大版字体</font>  

> 一级
>> 二级
>>> 三级
>>>> ......

---

被下划线加粗加大的字体
---

![pic 网址或者本地文件的相对路径/绝对路径](https://www.runoob.com/wp-content/uploads/2019/03/iconfinder_markdown_298823.png)

html换行<br>
html换页<div STYLE="page-break-after: always;"></div>

空格 &ensp;&ensp;&ensp;&ensp;&ensp; 空格 \&ensp;
$$
独占一行的居中数学公式 LaTeX
\delta(n)=\begin{cases}
    1, &n = 0 \\
    0, &n \neq 0
\end{cases}
\tag{1.1}
$$  
行内数学公式$x(n)=A \sin (\omega_0n + \phi)$
$ABCDEFGHIJKLMN$ 斜体  
$\rm{ABCDEFGHIJKLMN}$ 正体  

各级标题
# 1
## 2
### 3
#### 4
##### 5

流程图1
```flow
st=>start: 开始框
op=>operation: 处理框
cond=>condition: 判断框(是或否?)
sub1=>subroutine: 子流程
io=>inputoutput: 输入输出框
e=>end: 结束框
st(right)->op(right)->cond
cond(yes)->io(bottom)->e
cond(no)->sub1(right)->op
```

流程图2
```flow
st=>start: 开始框
op=>operation: 处理框
cond=>condition: 判断框(是或否?)
sub1=>subroutine: 子流程
io=>inputoutput: 输入输出框
e=>end: 结束框
st->op->cond
cond(yes)->io->e
cond(no)->sub1(right)->op
```

居中
| 11 | 12 | 13| 14| 15| 16| 17| 18| 19 | 20|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| D | C | C | A| B| A| C| D| B| A|

左对齐
| 11 | 12 | 13| 14| 15| 16| 17| 18| 19| 20|
|:-|:-|:-|:-|:-|:-|:-|:-|:-|:-|
| D | C | C | A| B| A| C| D| B| A|

右对齐
| 11 | 12 | 13| 14| 15| 16| 17| 18| 19| 20|
|-:|-:|-:|-:|-:|-:|-:|-:|-:|-:|
| D | C | C | A| B| A| C| D| B| A| 
-->