
# Hikari DEMO

## 此仓库用于演示Hikari在不同系统,基于LLVM10环境编译出来的DEMO(未进行符号strip)

### 备注: Hikari是类似OLLVM的混淆编译方案,原版只支持iOS/macos,且是较为古老的LLVM8,本人对其进行移植,添加Windows,Linux支持,并兼容最新LLVM版本

### DEMO编译环境如下:

### 1.基于[Hikari](https://github.com/HikariObfuscator/Hikari/tree/release_80)移植(Windows/iOS/macos/Linux),保留原版所有功能

### 2.LLVM版本:
```
clang version 10.0.1 (https://github.com/llvm/llvm-project.git eaae6dfc545000e335e6f89abb9c78818383d7ad)
Thread model: posix
```

### 3.目录`source-code`为DEMO源码, 目录`released`为编译后成品

### 4.本人只关心移植技术, Hikari相关版权属于原作者,侵删.

### 5.可有偿指导相关移植技术,有意可联系`base64: cW9rZWxhdGVAZ21haWwuY29t`
