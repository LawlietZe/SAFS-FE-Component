![N|Solid](/img/safs_logo.png)
# Fund 前端使用手册

## 内容弹窗</font>
  
![N|Solid](/img/dialog.JPG)

使用规范:   

务必引入fund-panel类，用于装载弹窗内容 

![N|Solid](/img/dialog-1.jpg)

内容规范：  

1. 确认、提交、新建按钮规范：统一放在下方，一列输入表单情况下应该与上方的input输入框左对齐,两列输入框情况下应该居中，按钮下方应该留足够空间显示errorMessage
2. label标签统一靠左对齐，分号（：）统一采用中文模式（全角）
3. 提交后提示文字规范：应该在按钮下方，并字体颜色统一为:ForeColor="red"，并且向上方label标签左对齐;

![N|Solid](/img/dialog-2.jpg)

## 列表

例子：

![N|Solid](/img/table.jpg) 

布局规范: 

整个列表必须左对齐，一般需要设置`padding:10px`

内容规范：

`首列左侧对齐`，`尾列右侧对齐`，`文本左对齐`，`数字金额右对齐`，`数字采用1,000,000.00格式` 

### 日期控件

例子：

![N|Solid](/img/s-date.jpg) 

布局规范: 

一般跟在label后面

内容规范：

标准日期格式，`0000-00-00`，控件高度`24px`，宽度`85px`,有时为了整体一致宽度可以`100px`，内容居中
