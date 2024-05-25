# mesa-patches
- **本仓库存放我的mesa补丁，基于MIT协议分发。**  
- **注意：请使用主线代码应用补丁。（2934e1f提交测试成功）**  
- **如果需要请求补丁更新，请提issue**  
---
## 如何使用？
_1. 克隆代码仓库 (**你首先需要安装git！**)_
- **主线**
```
git clone --depth=1 https://gitlab.freedesktop.org/mesa/mesa.git ./mesa-main/
cd ./mesa-main/
```
- **2934e1f**
```
git clone https://gitlab.freedesktop.org/mesa/mesa.git ./mesa-2934e1f/
cd ./mesa-2934e1f/
git checkout 2934e1fad52806b4904a22c037c564eba6e21c85
```
_2. 应用补丁 (**确保你在mesa代码库根目录下！**)_  
---
**温馨提示：辨别补丁类型请打开文件看diff命令的参数，包含--git是git patch；否则就是unix patch。**  
---
* _对于git补丁_  
`git apply /path/to/your/git_patch`  
* _对于unix补丁_  
`patch -p num -i /path/to/your/unix_patch` （num是跳过的目录层数，根据情况指定。一般都是1，跳过比对目录的第一层；补丁从根目录起的对应文件。）   
---
### 感谢
* [Termux Packages developers](https://github.com/termux/termux-packages "Termux Packages Github Repository")
* [XMeM](https://github.com/XMeM "XMeM Github")
* **JeezDizReez**
* **airidosas252**
* [alexvorxx](https://github.com/alexvorxx "alexvorxx Github")
---
_好的，没有什么要讲的了。END喽！_
