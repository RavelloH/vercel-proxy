# vercel-proxy / Vercel代理

## 使用:
任何`*.vercel.app`的域名都可更改为以下格式访问: 
```
   https://[Name].vercel.app/[urls]
=> https://vercel.z-blog.tk/[Name]/[urls]
```
如:
```
   https://163musics-api.vercel.app/search?keywords=NC
=> https://vercel.z-blog.tk/163musics-api/search?keywords=NC
```

## 用途:
代理API。请勿用于网页代理。

## 注意:
请勿用于网页代理，而且这根本行不通：现阶段直接指向网页会因为链接错误问题，无法获取相关资源。  
简而言之，就是：这个服务现在只能代理一个页面。无法引用其他资源。

## 原理:
用Vercel的`Rewrite`服务，使用国内可访问域名，达到代理目的。

## 部署:
- Clone/Fork此仓库 
- 使用Vercel部署
- 绑定一个国内可访问域名
