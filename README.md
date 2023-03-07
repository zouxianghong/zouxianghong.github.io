使用jekyll预览index.html
终端输入:
  ```
  jekyll serve
  ```
弹出网址即可预览

如果您想对主页进行改动
- fork该项目到您个人账户;
- 将所fork的该项目下载到您本地进行修改;
  ```
  # for windows
  下载git
  打开Git CMD
  cd到下载的文件夹
  # for linux
  打开终端，安装git
  cd到下载的文件夹

  git init
  git remote add origin git@github.com...(这里git@github.com是您fork的项目-code-SSH-复制的内容)
  ```
- 按照下述指南修改后
- 在您的个人帐户更新您fork的项目
  ```
  # 同样git到本地下载的文件夹
  git add .
  git commit -m "some commit"
  git push origin master
  ```
- 在您的个人帐户项目中新建pull request等待拉取。

以下为修改指南：
- 如果您想添加Academic Activities，请在index.html的：
  ```
  <p class="lead" style="border-bottom:1px solid #CCC">Recent News</p>
	<ul>
	<li><font color="red"><b>I am looking for self-motivated students, postdocs, research assistants and visiting scholars! Please <a href="contact">drop me an email</a> if you are interested in working with me!</b></font></li>
  ```
  下方加入：
  ```
  <li>Your news</li>
  ```

- 如果您想将您的论文添加到主页：
  - 请准备：
    - 一张长宽比近似3：2的代表性图片(jpg/png/gif);
    
      ```
      如果您提交mp4，请先压缩
      ffmpeg -i yourvideo.mp4 -r 20 -s 300*240 out.mp4
      ```
    
    - 文章标题;
    
	  - 作者全名;
	  
	  - 所发表期刊/会议，奖项/分区/CCF级别
	  
	  - 相关网址链接（paper，code，project，slides，videos...）
	- 将图片加入到您复制到本地的文件夹/publications/teasers
	- 组织如下代码：
	```
		<div class="before-item" >
		<div class="pubimg">
			<img  class="pubpic" src="teasers/yourpic.jpg">
		</div>
		<div class="pubdsp">
			<span class=pubtitle > 
				Your Title<br>
			</span>
			<span class=pubauthor > 
				Authors, <b>Zhen Dong</b>, Authors<br>
			</span>
			<span class=publoc > 
  			Your journal/reference (eg:CCF-A)<br>
  		</span>
  		<span class=publink>
  			[<a href="Your paper link">Paper</a>]
  			[<a href="Your code link">Code</a>]
  			[<a href="Your video link">Video</a>]
  		<br></span>
  	</div>
  </div>
  ```
  - 确认年份及分类（Multi-modal Data Fusion/Point Cloud Augmentation/Scene Understanding/Scientistic Calculation/Reconstruction/Others）
  - 在 publication/index.html中查找
    ```
    <p class="lead" style="border-bottom:1px solid #CCC">Your year</p>
    ```
    在其下方加入您的上述文章代码
  - 在publication/index_topic.html中查找
    ```
  <p class="lead" style="border-bottom:1px solid #CCC">Your topic</p>
    ```
    在其下方加入您的上述文章代码
  -如果您的文章被选为selected展示
    在index.html中
    ```
    <p class="lead" style="border-bottom:1px solid #CCC">Selected Publications</p>
    ```
    下方加入您的上述文章代码
  
- 如果您想将您的项目添加到主页，请在projects/index.html的列表中加入
  ```
  <li>名字,时间段,主持。</li>
  ```

- 如果您想添加Awards，请在index.html的对应位置：
  ```
  <p class="lead" style="border-bottom:1px solid #CCC">Awards</p>
  ```
  下的列表中加入
  ```
  <li>名称(年份)</li>
  ```

- 如果您想添加Academic Activities，请在index.html的对应位置：
  ```
  <p class="lead" style="border-bottom:1px solid #CCC">Academic Activities</p>
  ```
  下的列表中加入
  ```
  <li>名称</li>
  ```