# 微信情侣早安/天气推送    <br> <br>
### 语言使用的是PHP
    只需要修改配置文件config.php里的APPID和app_secret即可，模板id可以复制下面的推送模板内容到测试公众号里添加然后取id粘贴
    
    类型大同小异，只需要配置好config.php文件然后访问index.php即可推送了
    
    此开源代码适合情侣之间使用
    本来不想写的，但是网上好多都是少了点东西，此版本是修复之后可以正常使用的版本

    后面会更新多人推送版本，适合朋友，或者日常提醒等功能
        
    有什么问题可以联系：Noenvy
***
`推送模板` <br>
```html
{{date.DATA}} 
地区：{{region.DATA}} 
天气：{{weather.DATA}} 
气温：{{temp.DATA}}  
风向：{{wind_dir.DATA}} 
今天是我们恋爱的第{{love_day.DATA}}天  
{{birthday1.DATA}} 
{{birthday2.DATA}} 
{{love.DATA}} {{sjsj.DATA}} {{chp.DATA}}
```

