# 快速构建一个tomcat


## 已经打开权限和去掉ip访问限制  

分别配置在 `conf/tomcat-users.xml`  和 `webapps/manager/META-INF/context.xml`   
`配置文件`和`webapps`均基于`9.0.35`版本tomcat, 如果介时`tomcat:latest`有改动请自行变更所需要的文件  

## tomcat官网地址
https://tomcat.apache.org

## 相关目录
`conf:` /usr/local/tomcat/conf    
`webapps:` /usr/local/tomcat/webapps
`logs` /usr/local/tomcat/logs  

除上述以外其他均无改动!

## 用户名与密码(如需要修改请在docker-compose.yml自行配置)

```
用户名 tomcat
密码 123456
```
