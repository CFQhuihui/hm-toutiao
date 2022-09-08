# 黑马头条移动端app安装部署手册

## 项目安装依赖包
```
npm install
```

### 如果默认的源下载速度比较慢，推荐先换源再安装，此处使用的是阿里淘宝的源
```
npm config set registry http://registry.npm.taobao.org
npm install
```

### 下载依赖的操作中，如果遇到无法解析依赖树的问题（依赖冲突），尝试使用命令
```
npm install --legacy-peer-deps
```

### 启动本地项目
```
npm run serve
```

### 打包压缩项目
```

npm run build
```

### 检查修复
```
npm run lint
```
