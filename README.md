# lvgl模擬器
修改自[lv_port_pc_vscode](https://github.com/lvgl/lv_port_pc_vscode), 下载编译工具配置后直接使用

## Windows搭配VSCode使用
1. 下载编译工具[MinGW-W64](https://github.com/niXman/mingw-builds-binaries/releases/download/14.2.0-rt_v12-rev1/x86_64-14.2.0-release-posix-seh-ucrt-rt_v12-rev1.7z)，下载后解压到任意位置
2. VSCode安装插件CMake、CMake Tools
3. 设置CMake tools插件
   *  `Additional Compiler Search Dirs` -> 添加MinGW-W64工具解压后的bin目录
   *  `Status Bar Visibility` -> 更改为`visible`
4. 使用vscode打开模拟器工程
5. 点击底部状态栏`[未选择任何工具包]` -> `扫描工具包`
6. 再次点击`[未选择任何工具包]` -> `GCC 14.2.0 x86_64-w64-mingw32`
7. 点击三角图标编译运行