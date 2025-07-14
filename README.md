# nga帖子推荐/更新/回复代码

该代码作用为作者查看自己帖子的推荐/更新/回复

# 环境配置

1.webscraper 火狐和chrome均可

2.jupyter notebook 

# 适用流程
1.使用火狐或者chrome安装插件webscraper

2.在想要使用的帖子界面按F12进入开发者模式

3.点击webscraper
<img width="1920" height="824" alt="image" src="https://github.com/user-attachments/assets/558dc6ba-e871-47f5-9714-7c3105385b92" />

4.点击create new sitemap 并选择import sitemape
<img width="1920" height="764" alt="image" src="https://github.com/user-attachments/assets/3c66ab3b-e271-43ee-80ca-d10947ac4c6e" />

5.打开下载的sitemap文件，复制所有代码到webscraper json中后点击导入
<img width="1701" height="810" alt="image" src="https://github.com/user-attachments/assets/8abccb02-231e-447f-b624-260eb2503907" />
<img width="1920" height="490" alt="image" src="https://github.com/user-attachments/assets/db45dc0d-7f33-4a1b-bf2a-584cae6a565d" />
<img width="1910" height="456" alt="image" src="https://github.com/user-attachments/assets/2201a6e5-e8f3-40d0-9b69-83b6f47a80cb" />

6.在sitemap界面中点击导入的sitemap
<img width="1920" height="620" alt="image" src="https://github.com/user-attachments/assets/11bd6558-fa3a-4743-9d8b-f61ffb2b11a1" />

7.选中sitemap后点击顶端第二栏，选择edit metadata
<img width="1910" height="495" alt="image" src="https://github.com/user-attachments/assets/2f27571c-2d0e-4b73-bf5e-f23aad15cecb" />

8.在Start URL1 中输入自己的帖子链接，其中page=[x-y]是你帖子的页数范围，修改完成后点击save sitemap 保存
<img width="1920" height="484" alt="image" src="https://github.com/user-attachments/assets/f5959948-9585-4b58-b2c1-4940cc0f893a" />

9.点击顶端第二栏的sitemap calcute,选择scrape准备开始爬取
<img width="944" height="411" alt="image" src="https://github.com/user-attachments/assets/b097501b-5723-4b83-82dc-2d2c25392a8a" />

10.设置两个时长，参考网速设置，过短会导致采集不到数据，过长会导致耗时增加
<img width="716" height="161" alt="image" src="https://github.com/user-attachments/assets/b2cd4175-2bb4-41c9-b32b-b69f43da2396" />

11.等待数据采集完成后点击refresh data刷新数据
<img width="1920" height="530" alt="image" src="https://github.com/user-attachments/assets/e4a0b059-1fce-4ca1-8b95-5e69e7930754" />

12.点击顶端的sitemap calcute，选择export data 后点击.xlsx导出数据
<img width="980" height="459" alt="image" src="https://github.com/user-attachments/assets/fa1d9acc-04c5-47e9-9484-2cedc939c9b1" />
<img width="1191" height="450" alt="image" src="https://github.com/user-attachments/assets/82975ee3-ea67-40a6-9cae-015b75e311b3" />

13.将下载的文件移动到下载文件夹内的raw_data文件夹内，并使用当前日期为其增加时间戳
<img width="894" height="329" alt="image" src="https://github.com/user-attachments/assets/71d196b5-2404-4e09-918b-cbe3fbb6e2bc" />
<img width="845" height="300" alt="image" src="https://github.com/user-attachments/assets/ea21cfe7-fd35-42f2-bb33-8be1dc6cf184" />

14.打开jupyter notebook,打开proceed.ipynb文件
<img width="1476" height="406" alt="image" src="https://github.com/user-attachments/assets/a766bbde-f02a-440b-b1b4-707af7973739" />

15.点击第一个代码块并运行安装第三方包
<img width="1736" height="496" alt="image" src="https://github.com/user-attachments/assets/505350c9-7135-4c37-ac78-d78533364e01" />

16.点击第二个代码块导入代码需要的包
<img width="1429" height="656" alt="image" src="https://github.com/user-attachments/assets/e3f6efd3-2781-4483-bb07-e45f5296ba7d" />

17.点击第三个代码块并修改其中的datetime_last和datetime_this为上次和这次采集数据的日期后点击运行
<img width="1920" height="754" alt="image" src="https://github.com/user-attachments/assets/e08ee543-1bbf-418e-8637-e0b908d29c86" />

18.点击第四个代码块后修改其中的username为楼主用户名后，点击运行
<img width="1454" height="764" alt="image" src="https://github.com/user-attachments/assets/ab09b510-0c48-40bb-8037-c053396712df" />

19.运行结果如图
<img width="466" height="462" alt="image" src="https://github.com/user-attachments/assets/7446847a-6508-44c6-831f-636d4bae576a" />



















