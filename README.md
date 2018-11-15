# DAM

## 'learnSVG'——【非作业相关】练习svg
- embed.html
- example.svg
- icon.svg

## Hw02
- 音乐资源展示

## 'musicdisplay'——Hw02a
1. 增加spyder.py,可以爬取网易云指定歌单的歌曲。
2. 添加资源索引和分区索引，动态生成网页，使分区数可修改
3. 将播放和展示分离开，避免同时播放多首歌曲的问题产生
4. 增加读取.lrc标准文件功能
5. 固定展示框高度，并自动为内容溢出部分添加scroll

> 爬虫使用说明：
- （可选）建立文件夹，并且在/myapp/static/meta.json中输入新文件夹信息
- 在config.py中输出歌单id、下载到的文件夹名、分类名
- 运行spyder.py文件，下载资源，（如果建立了新文件夹，则网页中的分区数量会增加）

## 'watermarking'——HW03 Watermarking
1. Learn to add watermarking to image.
2. bonus:a simple web based service
3. use OpenCV
> 说明：
- CMD:`python runserver.py`

## HW04 Image Similarity Computing
1. Given 10 images, compute similarities between the first one and the others, and find the most similar image to the first one.
2. find some feature vectors on different scales.
3. How to compute similarity? 
	- 余弦相似度
	- 欧式距离
	- 其他距离……
4. 其他方法
	- 色彩空间
	- 纹理信息，滤波
	- ……
5. 多张图像
6. 其他文件格式


