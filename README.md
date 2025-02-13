> @createTime: 2024-01-09
> 
> @latestUpdateTime: 2024-01-09

## 项目介绍
兰州大学学工处管理科 - 后台开发

用于无《高校学生登记表》证明的开具

涉及表单信息搜集、django后台定制化开发等

![image](https://figs-bed-1307577475.cos.ap-nanjing.myqcloud.com/imgs-bed/20240109112951.png)

## 技术栈选型
- 前端：uniapp 用于制作微信小程序
- 后端：django 用于制作后台网站


## django 后台定制化开发
核心功能
1. To 毕业生【微信小程序端】收集毕业生信息 √
2. To 学校管理员【后台端】查看毕业生信息 √
3. To 学校管理员【后台端】审核毕业生信息 √
4. To 学校管理员【后台端】发送邮件信息（包含主题、正文和附件等） √

## 功能开发日志
基本功能
1. 样式 ✔
2. ajax调通  审核状态改变，审核操作按钮变为不可选  ✔
3. 前端联调  ✔
4. 发送邮件  ✔ 2024-01-07
5. 邮件时间  ✔ 2024-01-07
6. Push code to 微信小程序  ✔ 2024-01-09


extra:
1. 日志 用于追溯bug ✔ 2024-01-05
2. word生成

NEXT TODO：
1. 上线到微信小程序 等待相关资料的上传与微信官方的审核
2. 部署到学校服务器上，防止数据出域，数据安全保证


## 更新日志
### 2024.01.09
push 代码到 github 仓库

🌟 实现基本功能
1. To 学校管理员【后台端】查看毕业生信息 √
2. To 学校管理员【后台端】审核毕业生信息 √
3. To 学校管理员【后台端】发送邮件信息（包含主题、正文和附件等） √