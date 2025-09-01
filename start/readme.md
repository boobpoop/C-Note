# 1.确定本地有g++/clang依赖

g++ --version
Apple clang version 17.0.0 (clang-1700.0.13.5)
Target: arm64-apple-darwin24.6.0
Thread model: posix
InstalledDir: /Library/Developer/CommandLineTools/usr/bin

clang++ --version
Apple clang version 17.0.0 (clang-1700.0.13.5)
Target: arm64-apple-darwin24.6.0
Thread model: posix
InstalledDir: /Library/Developer/CommandLineTools/usr/bin

# 2.创建Myproject.cpp文件，编写代码


# 3. 编写完代码后，vscode会自动识别，提示安装c++环境。

# 4.执行并打印

![alt text](image/image-1.png)

# 5. 手动编译cpp

1. g++ start/MyProject.cpp 
生成a.out文件

2. g++ start/MyProject.cpp -o test_c++
生成test_c++文件

3. ./test_c++ 
执行test_c++文件

输出：Hello World