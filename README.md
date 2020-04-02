# SimpleNodeServer-Cli
SimpleNodeServe 脚手架

##  目录结构

```
├── bin
│   └── www             //可执行文件
├── dist
    ├── ...             //生成文件
└── src
    ├── config.js       //管理eos配置文件
    ├── index.js        //主流程入口文件
    ├── init.js         //init command
    ├── main.js         //入口文件
    └── utils
        ├── constants.js //定义常量
        ├── get.js       //获取模板
        └── rc.js        //配置文件
├── .babelrc             //babel配置文件
├── package.json
├── README.md
```

## 开始使用

### 安装

```
npm install -g simplenodeserver-cli
```

### 初始化 SimpleNodeServer

```
sns-cli init
```