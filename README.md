# dialogDiy
#注意，css和js或许要视项目微调下，比如css在rem布局时候，不居中,个别用到的px换成rem
#引入2个文件
```
<script src="...js/eject.js具体地址看项目...">
<link href="...css/eject.css具体地址看项目...">
```
<script>
#使用：
#1、alert弹窗调用示例：
```
Ealt.Ealert({
      title:'alert提示文案',
      message:'这是alert弹窗，感觉还是很不错的'
})
  ```
#2、confirm弹窗调用示例：
  ```
Ealt.Econfirm({
      title:'confirm弹窗文案',
      message:'这是confirm弹窗,你确定删除吗?',
      define:function(){
            alert('您点击了确定')
      },
      cancel:function(){
            alert('您点击了取消')
      }
})
  ```
#3、toast弱提示调用示例：
```
Ealt.Etoast('这是toast弱提示，您觉得怎么样！',3)//默认三秒
  ```
