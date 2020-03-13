# Valine Checker Admin
**🚧 WIP**

# 使用方法
## 安装依赖库
```bash
$ cd server
$ npm install
$ cd ../pages
$ npm install
```
## 调试
```bash
$ ./debug.sh
# or
$ ./debug.yarn.sh
```
`express` 运行的服务器在 `localhost:3000`，`vue` 运行的服务器在 `localhost:8080`。  

## build
```bash
$ ./build.sh
# or
$ ./build.yarn.sh
```

## 部署
首先 `build`，然后复制 `server` 文件夹到服务器上，运行 `express`:
```bash
$ npm run start
```


# FAQ
- **Q: 为什么代码写的这么垃圾？**  
  A: 别问，问就是没搞过前端。