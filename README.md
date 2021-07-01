# 项目名称

公司的后台管理系统，目前包含：

+ 千帆系统管理后台

## monorepo命令

+ "bootstrap": 将仓库中的依赖项链接在一起
+ "setup": 调用bootstrap并且调用libraries:build
+ "version:fix": 修复版本，将同一个库的多个版本进行同步
+ "version:check": 校验版本
+ "libraries:build":  打包libraries下的所有拥有build命令的包
+ "clean": 清空node_modules依赖包

