# auto_comment

## 已不可用，停止维护（2024/09/03)

可用[项目](https://github.com/6dylan6/jdpro)下的评价(jd_AutoEval.js)；

## JD自动评价

支持评价晒单（带两张图），追评，服务评价，支持AI生成评价内容

青龙拉库命令 ql repo https://github.com/6dylan6/auto_comment.git "jd_" "" "jdspider"

如果运行报依赖错误，运行评价依赖安装任务，没有问题不要运行

浏览器登录抓取CK（PC端CK），添加变量PC_COOKIE，每次运行评价10个订单

www的那个地址抓CK，登录后F12点到network，不要用命令document.cookie抓，会不完整，找带cookie的请求复制（其实只复制thor=xxx这串就行）

有问题欢迎提pr、issue

## 更新日志：

2022/11/6 新增多账号； 报错不停止运行；带两个图评价晒单；倒序评价，优先比较老的订单

2022/11/16 修复有些订单匹配不到pid；服务评价报错

2022/11/20 随机选取评价图片

2023/1/7 正常运行，有问题的多跑几次看看

2023/3/14 正常使用

2023/3/28 修复评价内容乱码

2023/4/19 添加gpt生成评价内容，当配置OPENAI_API_KEY环境变量启用，具体用法看注释（Cp0204的pr）

2023/4/22 移除openai依赖，优化代理方式，优化日志显示（Cp0204的pr）

2023/6/27 gpt错误跳出（Cp0204的pr）

2023/7/28 修复获取不到评价信息

2023/9/17 修复收集不到商品评价

## 运行例图（评价晒单基本是优质评价，评价有奖的订单可以获得奖励！！！）：

![image](https://i.postimg.cc/KznsXxfN/1.png)
