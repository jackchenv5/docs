# sonic 用户指南
## 仓库准备
> sonic-buildimage 仓库
```
git clone http://gitlabw.maipu.com/mp-sonic/sonic-buildimage.git
```
## 平台配置
```
make configure PLATFORM=centec PLATFORM_ARCH=arm64
```
### 虚拟机配置
```
make configure PLATFORM=vs PLATFORM_ARCH=arm64
```
