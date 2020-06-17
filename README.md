# ibm_cf_restart-actions
使用Github Actions定时重启IBM Cloud Foundry应用程序

## 使用之前，有几项准备工作
1. IBMCloud的账号密码
2. Cloud Foundry应用程序的区域
3. Cloud Foundry应用程序的名称

## 使用方法

### 1 Fork此仓库

### 2 设置此仓库的变量Secrets

依次添加名为
**IBM_CLOUD_ID**、**IBM_CLOUD_PWD**、**IBM_CLOUD_RGN**、**IBM_CLOUD_APP**的变量  
值分别为邮箱(账号)、密码、区域、Cloud Foundry应用程序的名称  

### 3 确定Github Action正常工作

点击star或者任意方法使Actions激活  

此前，可能需要点击**Pull requests**与**Projects**之间的**Action**进去点一下允许之类的

### 变量示例
IBM_CLOUD_ID====>12345@qq.com  
IBM_CLOUD_PWD====>123456QWER  
IBM_CLOUD_RGN====>us-south  
IBM_CLOUD_APP====>APP  

## 其他

配置完毕，将会在每周三的03:30重启Cloud Foundry应用程序
