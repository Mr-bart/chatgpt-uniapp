### [文档](https://rf5apizpls.feishu.cn/wiki/RJ7ZwCcLEisud7kJCivcU7QKnkc?from=from_copylink)  | [WEB演示](http://gpt-pc.oostar.cn)
### 项目说明
- JAVA+unipp开发的chatgpt程序
- 开发脚手架基于人人开源 https://gitee.com/renrenio/renren-security
- chatgpt JAVASDK 基于Grt1228大佬开源的,地址https://github.com/Grt1228/chatgpt-java
- java开发的chatgpt小程序  前端使用uniapp   可打包多端运行  APP  H5  公众号  小程序等 ,三级分销,卡密充值,提供opai的反向代理,
- 后台包括海报管理,充值配置管理,GPTKEY管理,用户管理,分销提现管理,问答模板配置,AI模配置等
- 基础的CHATPDF功能  会进一步完善这个
- 可使用三方转发的4.0，方便申请不下来官方key的使用
- 具体功能看演示(演示为商业版本)
- 后台演示地址(此后台修改的在演示前端不会有变化)
- WEB演示地址：http://gpt-pc.oostar.cn
- H5演示地址：http://gpt-h5.oostar.cn
- http://gpt-test-admin.oostar.cn
- 账号:ceshi
- 密码:ceshi
- 演示后台没有开放GPTKEY管理权限和支付管理权限
- JAVA后台仓库: https://gitee.com/Mr-bart/gpt-java.git
- 后台页面仓库地址 https://gitee.com/Mr-bart/chatgpt-admin-ui.git
- 商业版H5公众号和小程序演示: 
- ![输入图片说明](rdimg/gzh_qrcode.jpg)
<br>

### 进度说明
   
- 本月更新适配PC版本的前端

**本地JAVA部署**
- 通过git下载源码
- idea、eclipse需安装lombok插件，不然会提示找不到entity的get set方法
- 创建数据库renren_security，数据库编码为UTF-8
- 执行renren-api/db/chatgpt.sql文件，初始化数据
- 后台管理默认账号密码为admin
- 修改application-dev.yml文件，更新MySQL账号和密码
- 运行后在后台管理-->系统设置-->参数管理对应修改公众号/小程序等APPID

**本地后台管理VUE运行**
- 您需要提前在本地安装[Node.js](https://nodejs.org/en/)，版本号为：[12.x、14.x]，再使用[Git](https://git-scm.com/)克隆项目或者直接下载项目后，然后通过`终端命令行`执行以下命令。

```bash
# 切换到项目根目录

# 安装插件
npm install

# 启动项目
npm run serve
```
**本地UNIAPP代码运行**
- 修改utils/evn.js中的BASE_URL为你的api地址
- 修改utils/evn.js中的BASE_WS为你的ws api地址
- 修改utils/request.js中的BASE_URL为你的api地址
- 修改manifest.json中的小程序appid
```bash
# 切换到项目根目录

# 安装插件
npm install
```
<br>

<br>



<br>

### 项目截图(截图内容为商业版本)
**WEB页面**
![输入图片说明](rdimg/pc11.png)
![输入图片说明](rdimg/pc0.png)
![输入图片说明](rdimg/pc1.png)
![输入图片说明](rdimg/pc2.png)
![输入图片说明](rdimg/pc3.png)
![输入图片说明](rdimg/pc4.png)
![输入图片说明](rdimg/pc5.png)
![输入图片说明](rdimg/pc6.png)
![输入图片说明](rdimg/pc7.png)
![输入图片说明](rdimg/pc8.png)
**H5页面**
![输入图片说明](rdimg/qd1.png)
![输入图片说明](rdimg/2011697673225_.pic.jpg)
![输入图片说明](rdimg/qd3.jpeg)
![输入图片说明](rdimg/2021697673229_.pic_hd.jpg)
![输入图片说明](rdimg/2001697672274_.pic_hd.jpg)
![输入图片说明](rdimg/WechatIMG203.png)
![输入图片说明](rdimg/qd7.jpeg)
![输入图片说明](rdimg/qd8.jpeg)
![输入图片说明](rdimg/qd9.jpeg)
![输入图片说明](rdimg/qd10.jpeg)
**后台页面**
![输入图片说明](rdimg/ht1.png)
![输入图片说明](rdimg/ht2.png)
![输入图片说明](rdimg/ht3.png)
![输入图片说明](rdimg/ht4.png)
![输入图片说明](rdimg/ht5.png)
![输入图片说明](rdimg/ht6.png)
![输入图片说明](rdimg/ht7.png)
![输入图片说明](rdimg/ht8.png)
![输入图片说明](rdimg/ht9.png)
![输入图片说明](rdimg/ht10.png)
![输入图片说明](rdimg/ht11.png)
![输入图片说明](rdimg/ht12.png)

### 普通版本与商业版的区别
|  功能    |  基础版本   |  商业版   |
| --- | --- | --- |
|   用户管理  |   ✅  |   ✅  |
|   热门问题  |   ✅  |   ✅  |
|   AI    问答  |   ✅  |   ✅  |
|   问答记录  |   ✅  |   ✅  |
|   GPTKEY管理  |   ✅  |   ✅  |
|   三端登入  |   ✅  |   ✅  |
|   WEB端页面  |   ❌  |   ✅  |
|   CHATPDF  |   ❌  |   ✅  |
|   三方4.0  |   ❌  |   ✅  |
|   3.5和4.0不用收费模式配置  |   ❌  |   ✅  |
|   提问模板  |   ❌  |   ✅  |
|   VIP充值  |   ❌  |   ✅  |
|   问答币充值  |   ❌  |   ✅  |
|   GPT绘画  |   ❌  |   ✅  |
|   三级分销  |   ❌  |   ✅  |
|   邀请海报  |   ❌  |   ✅  |
|   合伙人模式  |   ❌  |   ✅  |
|   支付宝充值  |   ❌  |   ✅  |
|   微信充值  |   ❌  |   ✅  |
|   卡密兑换 |   ❌  |   ✅  |
|   分销提现  |   ❌  |   ✅  |
|   问答内容检测  |   ❌  |   ✅  |
|   FS绘画 |   ❌  |   ✅  |
|   SD绘画  |   ❌  |   ✅  |
|   二开帮助  |   ❌  |   ✅  |
|   专业售后服务  |   ❌  |   ✅  |

<br>


### 详细可联系

VX:扫以下二维码
![输入图片说明](rdimg/wx.png)
