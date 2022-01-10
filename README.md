# 介绍

该主题参考了集市中前期包括langzhou、VIWZ、Achuan2各位大大的样式，各位主题作者同样细心解答了我的问题，万分感谢

推荐码：ildAxIu，欢迎上车~

## 更新历史

之前比较懒....没有记录更新历史

### 2022.1.10

#### 添加了子弹流加强模式

根据logseq的主题作者pengx17的代码改造，效果如下：

![截图_20222410032423](https://user-images.githubusercontent.com/61633409/148697503-4e30d537-b1c3-44be-b199-da7fe36f6f96.gif)

列表中可以同一块多行，可以无序列表和有序列表混搭

但不可以和单独的文字、表格混搭（着重线会断...)，如果有好办法github告诉我哈~

##### 单独使用子弹流方式
1.将Bullet-Threading.CSS拷贝至主题css目录下

在css 首行 中添加：

```css
@import url("Bullet-Threading.css");

:root {
    --list-border-initial:                 #0442a5de;  /*列表大纲线颜色*/
    --list-border-focus:                   #f3722c;  /*子弹着重线颜色*/
    --list-bullet-focus:                   #4285f4;  /*bullet着重颜色*/
    --list-bullet-hover-background:        #4285f4;   /*bullet悬停背景色*/
    --list-bullet-fold-background:         #ffa801;  /*bullet折叠背景色*/
    --list-bullet-fold:                    #f3722c;  /*bullet折叠时着重颜色*/
}
```

### 2022.1.5

编辑区调整为纯色<br>添加了菜单线条、页签颜色<br>调整大纲、文档树样式颜色<br>侧边栏调整<br>修改全屏浏览<br>其他小调整

### 2022.1.4

不再使用毛玻璃效果

优化表格线条颜色

PDF浏览问题

### 2022.1.2

添加了文档树分割线

尽可能删减毛玻璃效果，提升性能
