### Star History 点亮项目星星！

[![Star History Chart](https://api.star-history.com/svg?repos=iCloudZA/CloudZA_API&type=Date)](https://star-history.com/#iCloudZA/CloudZA_API&Date)

## 前言
祝大家新年快乐，欢迎使用本程序(CloudZA API)

----

## 教程
> 以下是本程序的安装教程
### 环境支持
- PHP版本 8.0
- Mysql 5.6及以上
- Windows/Linux

## 安装
1. 将程序上传到网站目录配置伪静态规则
2. 访问domain或者domain/install进入到安装指引
3. 安装数据库/配置管理员账号以及密码即安装完成
4. 安装教程：https://www.bilibili.com/video/BV1uv4y1y749

## 添加API
> 本地API在目录`extend/api/`中添加文件即可，主文件以`index.php`命名
> 然后在后台添加API，类型有`本地`和`外部`，如果是`extend/api/`中的就选择本地API，如果是外链就选外部API

## 伪静态
```nginx
if (!-e $request_filename)
{
    rewrite ^(.*)$ /index.php$1 last;
}
```

## 免签约支付程序(朋友的)
https://github.com/kaindev8/starMQ

喜欢可以看看


## 赞助名单
|   昵称   |    联系方式    | 赞助方式 | 赞助金额 |
|:------:|:----------:|:----:|:----:|
|  客观手记  | 22****5716 | 支付宝  |  20  |
|   逢戏   | 13****9867 |  微信  |  10  |
| ℳℓ大鱼ℳℓ | M-****ish  |  微信  |  20  |

## 最后

> 开源不代表肆意的倒卖，请勿修改底部的Github链接，尊重开源精神谢谢🌹
