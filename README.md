## 介绍
* 基于百度AI平台及小程序云开发实现的植物识别Demo
- [百度图像识别接口文档](https://ai.baidu.com/ai-doc/IMAGERECOGNITION/8k3e7f69o)
- [云开发文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)
- [参考文章](https://wavedanger.github.io/pages/folder1/%E7%99%BE%E5%BA%A6AI-%E6%A4%8D%E7%89%A9%E8%AF%86%E5%88%AB%E5%88%9D%E6%8E%A2.html)
## 使用
1. 克隆仓库
```
git clone git@github.com:wavedanger/baiduai-demo.git
```
2. 进入云函数baiduai安装依赖
```
cd baiduai-demo/cloudfunctions/baiduai
npm install
```
3. 申请百度AI帐号并创建应用，替换云函数index.js中APPID/AK/SK，修改为自己百度ai的应用信息
4. 选择云函数环境，上传并部署云函数后即可使用


