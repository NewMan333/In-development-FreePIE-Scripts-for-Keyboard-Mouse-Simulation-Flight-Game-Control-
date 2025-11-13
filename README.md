# 关于键鼠模拟飞行控制的freePIE脚本
###### FreePIE-Scripts-for-Keyboard-Mouse-Simulation-Flight-Game-Control        
### 参照arma3的键鼠操控逻辑，基于freePIE+vjoy脚本，实现键鼠模拟飞行控制
###### a script based on FreePIE + vJoy to implement simulated flight game controls following the keyboard and mouse control logic of Arma 3.      
### 实现步骤
第一步，下载安装[Vjoy](https://github.com/shauleiz/vJoy)   ，这会安装 Monitor Vjoy、configure vjoy等软件，这两个是最重要的。在configure vjoy 里配置好虚拟轴并重启。<br/>
###### 备注：由于vjoy最多支持8个轴和128键，所以我设置了两个vjoy([1] [2])，详情见代码轴绑定。<br/><br/>
第二步，重启电脑后，下载安装[FreePIE](https://andersmalmgren.github.io/FreePIE/)<br/><br/>
第三步，在FreePIE里打开.py文件的脚本，并运行。<br/><br/>
最后，你需要在相关游戏里，将游戏键位与你的虚拟轴绑定（目前我只做了针对dcs 直升机的控制脚本，这并不适用固定翼）。
### 相关资源
这是我的b站账号：[一个赛似一个](https://space.bilibili.com/1771594975)，有一期视频讲述关于轴绑定的设置，关键词：用arma3的键鼠逻辑飞DCS。
### 更多建议
①目前脚本处于开发阶段，命名空间很乱。所以我建议你将脚本交给ai分析，由ai帮你分析各个代码的具体实现。也可以让ai帮你增加功能、更改设置。<br/><br/>
②感谢[爱认真的泡泡](https://space.bilibili.com/347194290) ，他介绍了这种实现方式。[DCS：World 鼠标模拟摇杆 | vJoy 虚拟游戏控制器](https://www.bilibili.com/opus/697225740818579477)，他是基于[此贴](https://www.lfs.net/forum/post/1862759)完成的代码<br/><br/>  
③还有一个软件同样实现了键鼠模飞控制，我们在控制方式上有一些不同，但他关于摇杆、总距、脚舵的曲线设置非常不错，还有很多有用的小功能。如果你觉得我的脚本不适合你，试试这个由[Dawson924](https://space.bilibili.com/1738605283)制作的软件：[MouseFlightControl](https://github.com/Dawson924/MouseFlightControl/)<br/><br/>
### 告白
我非常喜欢arma3，原因之一是在这款游戏中既能扮演普通士兵，操作各类武器，也能驾驶不同的载具。键鼠的优势在于通用性极强，能让桌面保持整洁，且可随时切换不同游戏场景。这也是我投入大量精力实现键鼠模拟飞行控制的核心原因。<br/><br/>
我用我真实的感受告诉你，我的朋友，用键鼠玩模飞，同其他外设一样，你收获的乐趣不比任何人少。
