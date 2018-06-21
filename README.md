# joys-react-scripts

```
 create-react-app --scripts-version=joys-react-scripts my-app
```

## 创建项目步骤
如果项目没有内容：


    echo "# 项目名称" >> README.md

    git init   //初始化

    git add README.md

    git commit -m "first commit"

    git remote add origin https://github.com/aiaxia/react-dva.git   //项目地址

    git push -u origin master  //提交主干

    

如果已经有内容:


    git remote add origin https://github.com/aiaxia/react-dva.git

    git push -u origin master

## 目录结构

config 配置

build 打包

public 同步打包好的代码，用于服务器

src 开发

typings typescript类型文件

view html 模板

## 提交日志格式：

[C] Comment: 一般注释

[D] Docs: 修改了文档

[D] Release: 发布注释

[F] Fixed #2245: 修复一项 BUG

[A] Feature #1190: new feature added. 添加了一项新功能

[A] Added #2108: same as feature. 添加了一项新功能

[R] Removed #985: 移除

[D] Deprecated #1138: 一项功能过时/弃用
[I] Improved #186: 改进/提升

[X] Debug: 调试 /file/path:12

[-] Misc : 其它/杂项

[~] Initial.

GIT commit 注释按照相同的规则
