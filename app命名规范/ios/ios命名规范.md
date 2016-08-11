*

Title: Ios App 命名规范

Description: 简要ios app 命名规范

Author: Quant

Date: 20150801

*

#目录

[文件目录folder](#folder)

[控件id](#controlid)

[资源文件(resources)](#resources)

<div id="folder"></div>

##文件目录folder


**文件目录（folder）:采用驼峰命名，首字母大写。**


|包名							|说明		                                                           |
|-------------------------------|----------------------------------------------------------------------|
|Framesworks                    |放置系统framesworks|
|Resouces                       |资源文件|
|Resouces/Coredata              |Coredata相关配置文件|
|Resouces/Image                 |图片|
|Resouces/PList                 |plist配置文件|
|Resouces/Sound                 |声音文件|
|Resouces/UI                    |用户界面配置文件 xib & storyboard|
|Resouces/Localizable           |国际化文件|
|ThirdParty                     |第三方的文件,子目录按照 /公司名字/项目名字\_版本号 eg:ThirdParty/UMeng/UMFeedback\_3.5.0|
|Src                            |代码文件根目录，AppDelegate直接放置到该级目录下|
|Src/Controllers                |View Controllers|
|Src/CoreDate                   |CoreDate相关|
|Src/Database                   |数据库相关|
|Src/Entity                     |实体类|
|Src/Network                    |网络相关|
|Src/Utils                      |功能类|
|Src/Widget                     |自定义组件|
|Src/Dialog                     |dialog类|
|Src/Interface                  |接口|
|Src/Listener                   |监听器|
|Src/Config                     |配置|
|Src/Constant                   |常量|


<div id="controlid"></div>
##控件id

采用简写或全拼

|控件|缩写|例子|
|----|----|----|
|UIButton|btn|okBtn|
|UILable|lab|titleLab|
|UIView|view|backgroundView|
|UITabBar|tabBar|mainTabBar|
|UITableView|tableView|userInfoTableView|
|UISwitch|switch|leftSwtich|
|UITextField|textField|rightTextField|
|UIProgressView|progressView|downloadProgressView|
|UIImageView|imageView|avatarImageView|

<div id="resources"></div>
##资源文件(resources)

######PLIST
**module**

	eg:City.plist 
   		UserInfo.plist


######布局文件

#######文件命名
**module**

	eg:Main.stroyboard 
   		LaunchScreen.xib 
   		LoginDialog.xib

#######segu Identifier
**toModule**

	eg:toShareView

######Sound
**module**

eg:alarm.wav 
   eq_alarm.wav

######图片

#######图标
**ic_module**

	eg:ic_login_title.png
    
#######背景图片
**module_bg_name**

	eg:login_bg.png

#######button
**module_btn_name**

	eg:login_view_btn_login_normal.png

   		login_view_btn_register_normal.png
   
   		login_view_btn_register_pressed.png
   
   		login_view_btn_register_disabled.png
 
#######other
**module_xx.png**
   

###注:
<font size=3 color="#FF0000">代码中不要出现中文(注释除外)</font>
****



- 初稿









































