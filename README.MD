### lenneth-v2

> 说明
项目参照[lenneth](https://github.com/soraping/lenneth)，重写部分功能代码，所以lenneth-v2 是一个改版工具

> 问题
@ServerSettings 
  imports 会多一层路由名字
  configurations 配置类当成拦截类
  dev 环境配置使用问题

@RequestParam 绑定单个变量

> 版本
>> v1.0.1: Setting增加多个配置类字段[configurations]
>> v1.0.0: Setting增加多个拦截类字段[interceptors]


> 安装

```bash
拉取项目, 安装
npm install
```

```bash
构建
npm run build:prod
```

```bash
推送
npm run deploy
```