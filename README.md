# 项目背景
面对高校扩招、优胜劣汰的形势，图书馆座位资源紧缺必不得已。随着网络信息技术的发展和物联网技术的成长，各类基于计算机相关技术的座位预定系统都应运而生。
# 功能描述
## 管理员模块
广告页管理——对客户端广告页的广告图片进行增减、选择是否显示，并可对广告图片的轮播位置进行设置<br>
新闻资讯管理——对客户端的新闻资讯内容进行增删改<br>
评论管理——对用户在论坛上发表的评论进行管理，可删除也可选择不显示<br>
图书馆管理——对图书馆分区，楼层以及每层包含的座位数进进行修改和增添<br>
用户管理——对所有用户的个人信息进行增删改，并可添加新用户和删除已有用户<br>
论坛管理——对用户在论坛上发表的帖子进行增删改<br>
## 普通用户模块
座位预定——可选择空闲可被预定的座位进行预定<br>
座位预览——该界面提供用户选择的图书馆区域的相应楼层的座位预览图，并通过颜色区分座位的状态：红色为已被预定的座位，<br>
入座、离座——用户在我的预定界面可以点击入座，评论后离座<br>
通知公告——在客户端主界面用户点击资讯可以查看新闻资讯详情<br>
论坛交流——在论坛界面用户可以发表帖子，内容可以是文字和图片，也可以在其他用户发表的帖子在评论<br>
账号管理——用户可以在个人信息界面对自己的信息进行修改<br>
# 开发环境
IntelliJ IDEA 2019.2.2 x64 <br>
android studio 4.0 <br>
SQLyogEnt <br>
# 部署步骤
## Java 运行环境部署
1.下载java开发工具包JDK，下载地址：http://www.oracle.com/technetwork/java/javase/downloads/index.html <br>
2.选择Windows x64下载 <br>
3.下载后JDK的安装根据提示进行 <br>
4.安装完成后，右击"我的电脑"，点击"属性"，选择"高级系统设置" <br>
5.选择"高级"选项卡，点击"环境变量" <br>
6.在 "系统变量" 中设置 3 项属性，JAVA_HOME、PATH、CLASSPATH(大小写无所谓),若已存在则点击"编辑"，不存在则点击"新建" <br>
7.变量设置参数如下： <br>
变量名：JAVA_HOME <br>
变量值：C:\Program Files (x86)\Java\jdk1.8.0_91        // 要根据自己的实际路径配置 <br>
变量名：CLASSPATH <br>
变量值：.;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar;         //记得前面有个"."  <br>
变量名：Path <br>
变量值：%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin; <br>
8.配置完成后，可点击"开始"->"运行"，键入"cmd"，键入命令: java -version，出现以下信息，说明环境变量配置成功：java version "1.8.0_91" <br>
## IntelliJ IDEA
1.打开官网：http://www.jetbrains.com/idea/ ，点击页面中的“DOWNLOAD” <br>
2.选择下载IntelliJ IDEA 2019.2.2 x64 <br>
3.双击下载好的安装包 <br>
4.在弹出的界面点击“Next” <br>
5.选择安装位置，然后点击“Next” <br>
6.勾选安装选型，然后点击“Next” <br>
7.点击“Install”，进入安装 <br>
8.安装完成，点击“Finish” <br>
9.双击安装好的桌面IntelliJ IDEA图标 <br>
10.在弹出的界面点击“OK” <br>
11.勾选同意，再点击“Continue” <br>
12.选择“Skip Remaining and Set Defaults”  <br>
## android studio
1.下载Android studio安装包，可以从 http://www.android-studio.org/ 下载 <br>
2.下载后进行安装，点击"next" <br>
3.点击"Finish" <br>
4.在弹出界面点选第二个：Do not import settings <br>
5.根据提示安装选择：Custom <br>
6.风格可自行选择 <br>
7.根据提示点击"next"，等待安装 <br>
8.完成上面的步骤，将看到结束按钮，并可以在欢迎界面中打开 Android Studio 项目 <br>
## SQLyogEnt
1.下载sqlyog：http://pan.baidu.com/s/1i5j4GG9 <br>
2.双击sqlyog图标 <br>
3.选择Chinese，点击"OK" <br>
4.选择“下一步”三次后，选择合适路径安装 <br>
5.安装完成后点击“下一步”、“完成”  <br>
## 项目导入
1. <br>
2. <br>
3. <br>
4. <br>
5. <br>


# 项目结构

# 项目运行测试方法



# 联系方式
2758685939@qq.com
