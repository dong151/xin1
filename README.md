# multi_function_github
运行环境：Java8，maven

有脚本运行问题可关注微信公众号: **卷福同学** , 公众号内询问

## 京豆脚本使用
- 修改application.properties文件里jd.pt_key和jd.pt_pin为你的Cookie里的pt_key和pt_pin
- 运行MultiFunctionApplication类下的main函数启动项目
- 项目启动后，浏览器打开http://localhost:8080/doc.html#/default/jd-service/getJDUsingGET 可调试签到任务，入参和任务关系为：
    - 1 : 京东每日签到任务
    - 2 : 摇京豆签到
    - 3 : 抽京豆
    - 4 : plus会员签到

## 更新
- 2022.05.01 新增自动签到定时任务：摇京豆签到、抽京豆任务、plus会员签到。接口文档可视化界面
- 2022.04.27 新增服务探活接口和部署脚本deploy.sh，可用于阿里云云效自动化部署 具体部署步骤见博客：[2分钟教你部署2048小游戏到云服务器](https://blog.csdn.net/qq_36624086/article/details/123777993)