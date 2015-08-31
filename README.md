### steel
新浪微博steel框架开发流程

![steel开发流程图](https://github.com/zhiqiang21/steel/blob/master/steel开发流程.png)


####steel目录结构

.
|----server_back
|    |----aj                        //aj接口，仿真数据接口定义文件夹
|    |----h5                        //加载“首屏”页面文件夹
|    |----base.jade                 //页面公共文件定义
|----server_front                   //编译后文件夹（详情见src）
|    |----css
|    |----js
|    |----_html
|    |----img
|         |----app
|         |----common
|         |----components
|         |----lib
|         |----tpl
|         |----trans
|         |----ui
|         |----util
|----src                            //源代码文件夹
|    |----_html                     //html静态文件文件夹
|    |----css                       //样式存放目录
|    |----img                       //图片存放目录
|    |----js                        //js文件目录
|         |----app                  //路由配置文件
|         |----common               //公共组件目录
|         |----components           //"组件"目录
|         |----lib                  //库文件夹（STK，zepto，jQuery）
|         |----tpl                  //模板文件夹
|         |----trans                //aj接口文件夹
|         |----ui                   //ui组件文件夹
|         |----util                 //公共方法文件夹
|----gulpfile.js
|----package.json
