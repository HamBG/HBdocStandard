*

Title: Android App 命名规范

Description: 简要android app 命名规范

Author: xz

Date: 20150625

*

# 目录

[包package](#package)

[控件id](#controlid)

[布局文件(Layout)](#layout)

[资源文件(drawable)](#drawable)

<div id="package"></div>

##package


**包（packages）: 全部使用小写字母。**

**一级包名为com**

**二级包名为gexin(getui)**

**三级包名根据应用进行命名**

**四级包名根据类的具体功能类型命名**



eg:com.getui.gehuo.activity


|包名							|说明		                   |
|------------------------------|----------------------------|
|com.getui.xx.activity			|Activity类  |
|com.getui.xx.entity			|实体|
|com.getui.xx.adapter			|页面用到的Adapter类 (适配器的类)|
|com.getui.xx.util			|工具包类|
|com.getui.xx.logic			|逻辑类|
|com.getui.xx.db.dao			|数据库dao and entity类|
|com.getui.xx.db.logic			|logic|
|com.getui.xx.net.entity			|网络实体类|
|com.getui.xx.net.logic			|网络逻辑|
|com.getui.xx.service			|service服务|
|com.getui.xx.receiver			|Broadcast服务|
|com.getui.xx.interface			|接口|
|com.getui.xx.dialog			|dialog类|
|com.getui.xx.fragment			|fragment类|
|com.getui.xx.constant			|常量包类|
|com.getui.xx.config			|配置类|
|com.getui.xx.listener			|监听器|
|com.getui.xx.模块名称.api | 独立或第三方模块包|
|com.getui.xx.widget			|自定义控件|
|com.getui.xx.widget.xx			|自定义控件xx|


<div id="controlid"></div>
## 控件id

以缩写为主，部分语义不明确的采用简写或全拼

|控件|缩写|例子|
|----|----|----|
|LinearLayout|ll|llMain|
|RelativeLayout|rl|rlMain|
|FrameLayout|fl|
|AbsoluteLayout|al|
|TextView|tv|tvTitle|
|Button|btn|btnLogin|
|ImageButton|iBtn|iBtnLogin|
|ImageView|iv|
|CheckBox|cb|
|RadioButton|rb|
|EditText|et|etPwd|
|ProgressBar| proBar|
|SeekBar|skBar|
|AutoCompleteTextView|autoTv|
|WebView|wv|
|Spinner|spn|
|ScollView|sv|
|ListView|lv|
|ExpandableList|explv|




<div id="layout"></div>
## 布局文件(Layout)

###### 1、Activity
**activity_module.xml**

	eg:activity_main.xml、activity_splash.xml
	
###### 2、Dialog
**dlg_module.xml**

	eg:dlg_error.xml、dlg_progress.xml

######3、fragment
**fragment_module.xml**

	eg:fragment_ad.xml、fragment_setting.xml

###### 4、listitem
**listitem_module.xml**

	eg:listitem_ad.xml、listitem_city.xml

###### 5、widget
**widget_module.xml**

	eg:widget_weather.xml

##### 6、include
**include_module.xml**

	eg:include_head.xml、include_foot.xml


<div id="drawable"></div>
##资源文件(drawable)

###### 图标
**ic_module**

	eg:ic_login_title.png

###### 背景图片
**module_bg_name**

	eg:login_bg.png

###### button
**module_btn_name**

	eg:login_view_btn_login_normal.png

   		login_view_btn_register_normal.png
   
   		login_view_btn_register_pressed.png
   
   		login_view_btn_register_disabled.png
   
   		login_view_btn_register_pressed.xml(shape)
   		
**selector**
   **login_view_btn_register_selector.xml**
 
###### other
**module_xx.png**
   

### 注:
<font size=3 color="#FF0000">代码中不要出现中文(注释除外)</font>
****



- 初稿