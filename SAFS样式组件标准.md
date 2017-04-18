![N|Solid](/img/safs_logo.png)
# Fund 前端使用手册
version 1.0.0   2017/04/17
auth:Fund-FE team
## 容器规范
为保证设计的一致性，我们为页面设定了统一的容器范围，让信息能保持在固定的位置，ring器是用来收纳盒组织对象的存储器，理论上信息不应该超出容器范围。

----------

### <font color="#D0104C">组件名：dialog弹出框</font>
例子：  
![N|Solid](/img/dialog.JPG)

布局规范:  
弹出框具体扩展大小根据展示内容决定，不应该超出内边距。内边距(padding)设置: 
 引入fund-panel类 

```
.fund-panel {
    padding: 30px 15px 20px 25px;
} 
```

![N|Solid](/img/dialog-1.jpg)

内容规范：  

1. 确认、提交、新建按钮规范：统一放在下方，一列输入表单情况下应该与上方的input输入框左对齐,两列输入框情况下应该居中，按钮下方应该留足够空间显示errorMessage
2. label标签统一靠左对齐，分号（：）统一采用中文模式（全角）
3. 提交后提示文字规范：应该在按钮下方，并字体颜色统一为:ForeColor="red"，并且向上方label标签左对齐;
![N|Solid](/img/dialog-2.jpg)

### 组件名：table列表

例子：

![N|Solid](/img/table.jpg) 
布局规范: 

整个列表必须左对齐，一般需要设置padding:10px

内容规范：

`首列左侧对齐`，`尾列右侧对齐`，`文本左对齐`，`数字金额右对齐`，`数字采用1,000,000.00格式` 
