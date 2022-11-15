# 三维可视化Demo

## 下载打包后程序(releases)

1. https://github.com/inveta/demo/releases
2. 选择最新版下载zip包，解压
3. 运行bat文件，只支持Windows
4. 此时会弹出信令窗口，同时会打开网页

## 开发

```
# 下载源代码
git clone https://github.com/inveta/demo.git --recurse-submodules

# 添加 PLSB、singleTon、peer-stream
git submodule add https://github.com/inveta/PLSB Plugins
git submodule add https://github.com/inveta/SingleTon Plugins
git submodule add https://github.com/inveta/peer-stream

# 更新所有子模块
git submodule update --remote
```

## 注意事项

- NodeJS 16 以上: https://nodejs.org/
- Windows 10 以上
- 独立显卡nVidia或AMD，不能太旧
- Chrome或Edge或Firefox
- 如果提示没装DirectX，下载UEPrereqSetup_x64.exe并安装
- 压缩包内内置了node_modules，无需再手动安装依赖