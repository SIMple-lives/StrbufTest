<<<<<<< HEAD
# StrbufTest
这是我的StrubufTest的完成版本
=======
## StrbufTest

[![CC BY SA 4.0](https://img.shields.io/github/license/XUPTLinuxGroup2020/Favorites?style=flat-square)](https://creativecommons.org/licenses/by-sa/4.0/)

本仓库用于本地测试Strbuf任务

## 环境搭建
cmake的版本应大于等于3.14

ubuntu用户安装cmake
```sh
sudo apt install cmake
```
arch系用户安装cmake
```sh
yay cmake
```
---

fork该仓库到本地
```sh
git clone git@github.com:xiyou-linuxer/StrbufTest.git 
```

## 测试流程

进入strbuf目录
```sh
cd StrbufTest/strbuf
```
例如：\
张三若想在 `strbuf` 这项练习中测试代码，则需在 `strbuf` 目录下创建 `ZhangSan.c`
```
strbuf
├── FileTest
├── strbuf.h
├── test.cpp
└── ZhangSan.c
```
测试代码\
```sh
./test.sh
```
当出现下面的字样时，说明你已经通过了所有的测试点
```
[----------] Global test environment tear-down
[==========] 38 tests from 5 test suites ran. (1 ms total)
[  PASSED  ] 38 tests.

```

### LICENSE

本项目采用[知识共享署名-相同方式共享 4.0 国际许可协议](https://creativecommons.org/licenses/by-sa/4.0/)进行许可．
贡献本仓库视为同意贡献内容基于上述协议授权．

![知识共享许可协议](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)
>>>>>>> 5e2e845 (finish Strbuf)
