# frontend-nanodegree-Website-Optimization
##如何打开文件:
- 将views/pizza.html用浏览器打开；
- 将index.html用浏览器打开

##我是如何优化index.html的
 - 去除外联css，减少搜索文件的时间
 - 将所有的js代码加上assync属性
 
 
##我是如何优化views/js/main.js的:
- 将css文件以及js文件放到html的末尾；
- 修正changePizzaSizes，以解决dom的重复性选择以及FSL问题；
- 修正updatePositions：将layout的提取放在循环前面
