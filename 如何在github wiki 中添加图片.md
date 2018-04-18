在学习 redis 过程中，在GitHub Wiki中做笔记时遇到添加图片的问题。  
这里是在网上整理的 在Wiki中添加图片的步骤  

1. clone wiki  

2. 创建图片目录  

3. 在图片目录中添加图片  

4. 在wiki中引用图片  

***
具体操作步骤如下：  

1. clone wiki   

`git clone https://github.com/xx/xx.wiki.git  `

该url可以从clone this wiki locally 拿到  

2.创建一个images目录  

`cd xx.wiki  `

`mkdir images  `

3. 把文件添加到图片目录中  

`cp a.pn images/  `

`git add -A  `

`git commit -m "add a.png"  `

`git push  `

4.  在wiki文件中引用图片  

`vim test.md`

按 i 进入编辑模式 在你想要添加图片的位置，加入下面的代码

`[[images/a.png]]  `

git 添加 提交 push 一套带走  

参考博客  
<a href="https://blog.csdn.net/ge23456789/article/details/77338242">如何在github的wiki中添加图片</a>   
<a href="https://cloud.tencent.com/developer/ask/75655">将图像嵌入到GitHubwiki(Gollum)存储库中？</a>  
