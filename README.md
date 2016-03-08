# sizeCLass
横竖屏中屏幕约束设置
<br />
使用autolayout对屏幕适配，通过对横竖屏设置不同的约束可以达到横竖屏显示不同的效果。
<br />
#### 设置格式：<br />

>1.iPhone4S,iPhone5/5s,iPhone6<br />

竖屏：(w:Compact h:Regular)<br />

横屏：(w:Compact h:Compact)<br />

>2.iPhone6 Plus<br />

竖屏：(w:Compact h:Regular)<br />

横屏：(w:Regular h:Compact)<br />

>3.iPad<br />

竖屏：(w:Regular h:Regular)<br />

横屏：(w:Regular h:Regular)<br />

>4.总结<br />
如果项目不支持横屏显示,使用w:Compact h:Regular(或者直接取消使用Size Class) <br />
如果项目支持横屏显示,使用w:Compact h:Regular+w:Any h:Compact <br />
对于一些公有的约束(任意组合中都适用),一般放在w:Any h:Any中设置 <br />
iPad同理<br />
