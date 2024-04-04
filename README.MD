<p align="center">
    <img alt="logo" src="https://gongyue-shop.oss-cn-hangzhou.aliyuncs.com/uniappx.png" width="120" height="120" style="margin-bottom: 10px;">
</p>
<h3 align="center" style="margin: 30px 0 30px;font-weight: bold;font-size:40px;">UniApp-X TMP</h3>
<h3 align="center">UniApp-X骨架模板</h3>

## 说明

UniApp-X TMP，是基于[uni-app-x](https://uniapp.dcloud.net.cn/uni-app-x/)的项目骨架模板。集成实际业务中所需的各种封装工具，使开发者快速上手开发或项目二开。

## 目录骨架
- common 			为公共css集成
  * common.css		是用户自定义全局样式文件
  * icon.css		是字体图标文件
  * main.css		是全局原子css文件
  * uni.css			是uniapp初始化css文件

- components		为自定义组件目录
  * common			是公共组件目录
  * global			是全局组件目录
  * pages			是页面组件目录

- pages 			为一级路由栈页面
  * account			文件夹内是登录注册页面以及组件
  * tabbar			文件夹内是tabbar底部导航栏对应的页面

- static 			为静态资源目录
  * 资源类型应做分类存放，再基于所属页面存放对应静态资源

- utils				为项目工具函数目录
  * request			是uView的请求封装库
