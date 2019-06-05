# 在ts中import js模块

为了保证类型系统的完整性，如果想在ts中引用js模块，需要添加一个类型声明文件

命名规则为: xx.js -> xx.d.ts

然后就可以愉快的使用了

```bash
$ npx ts-node index.ts
3
```
