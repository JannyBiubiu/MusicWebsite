# MusicWebsite
Learn to build a website

## Branch: Watermarking
Learn to add watermarking to image.
bonus:a simple web based service
use PIL

file structure:

- README.md<br>				
//help
- requirement.txt<br>		  
//应用
- test.py<br>				  
//生成图片，使用PIL，最终没有应用到网页服务中，是否存在不影响
- extract.py			   
//提取水印，使用PIL，最终没有应用到网页服务中，是否存在不影响
- runserver.py			 
//运行此文件，启动后端服务<br>
- myapp					 
//应用<br>
	- __init__.py		  
	//初始化<br>
	- view.py			  //路由<br>
	- __pycache__		  //编译缓存，是否存在不影响<br>
	- static			   //静态资源，样式、字体、图片<br>
	- templates			//页面<br>
		- index.html	   //首页&生成图片的页面<br>
		- layout.html	  //布局<br>
		- test.html		//提取水印的页面<br>

