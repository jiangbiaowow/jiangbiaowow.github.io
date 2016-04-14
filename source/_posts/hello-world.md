
# ready()与onload的区别 #

**1.onload没有简写形式,ready具有简写形式，简写形式如下:**  
	

    $(document).ready(function(){})   
    $().ready(function(){}) 
    $(function(){})

**2.&nbsp;onload必须等待HTML页面中所有内部都加载完毕后才执行；ready是等待DOM节点树的内容加载完毕后就执行**  

**3.&nbsp;一个HTML页面只能编写一个onload；但是一个HTML页面允许编写多个ready**  

**注：可以利用此制作页面加载转圈效果**