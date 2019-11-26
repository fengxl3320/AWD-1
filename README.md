# 急需反馈，请用过的师傅有任何问题，意见和建议，都请联系作者交流！

# awdphpspear

## 米斯特安全团队

![image](https://github.com/ZacharyZcR/AWD/blob/master/image/True_Mst.png)

放错了...

![image](https://github.com/ZacharyZcR/AWD/blob/master/image/False_Mst.png)

### AWD线下攻防常用库 基于Python2.7

Author:ZacharyZcR@hi-ourlife.com

Extend_Module Author:@Virtua1

### Vision 0.1.7

增加了内存反弹shell马，具体操作详情请看新更新的文档。

另外集成了一个即用的工具。

pip install awdphpspear

python

from awdphpspear import *

start()

即可使用。

### Vision 0.0.7

主要更新了防御模块。

修复了一些bug，之前流量监控脚本和文件守护脚本无法同时开启，现在文件守护脚本不会守护txt文件了，所以流量监控生成的日志不会再被移除。

移除了一些文件守护版本不成熟的功能。

增加了文件监控，不会自动修复了，避免权限问题。

2019年9月23日

### Vision 0.0.5

增加了流量混淆的功能，增加了php文件列表功能，把RCE功能改为交互模式，修复了一些小BUG。2019年9月4日

#### 停止对之前AWD框架的一切更新，但不会移除项目，有需要的师傅可以自取，对于一些基本操作不是很明白的师傅可以参考里面的脚本思路。

#### 写在前面

经过深思熟虑，我把之前的脚本全部扔进了回收站。

不是它没有可取之处，而是因为它违背了AWD的本质。

不会有一个可以通杀一切比赛的脚本，尤其是在攻击方面。

每一次AWD比赛的漏洞点和EXP都相差甚远，想用一个刻板死硬的框架把它限制住是不可能的。

所以我改变了之前的思路，把成熟但一成不变的脚本尽数删除，将里面重复无用的代码抹去，尽量简化后封装成方法和函数。

通过组合这些基础的函数和方法，可以简单的模拟出大规模批量的攻击流量，迅速反应getshell。

内置的一些AWD常用种马，读取flag等操作可以可以在getshell后迅速打穿服务器并维持权限。

不破不立，破而后立，无招胜有招。

这应该才是AWD的精髓所在。

希望这些东西，能够帮到有需要的师傅，即使微不足道对我来说也很足够了。

#### 如何安装

需要pip支持

pip --version #查看本地pip版本

curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py   # 下载安装脚本

sudo python get-pip.py    # 运行安装脚本

Ubuntu 和 Debian 可用

sudo apt-get install python-pip

安装完pip后，执行如下命令

pip install awdphpspear

在Python环境下，import awdphpspear无报错即可正常使用。

#### 如何使用

详尽的操作手册请见awdphpspear目录下awdphpspear_readme.docx。

#### 联系方式

QQ:2903735704

邮箱:zacharyzcr@hi-ourlife.com