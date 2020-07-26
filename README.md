# ikbc_led_light
ikbc经典版加灯
G系列有些版本 虽然预留加灯的引脚 但需要升级固件才可以点亮
我是IKBC G-87版
通过以下方式完美解决了问题


## 固件升级
直接运行bin中exe程序即可
同时注意：
1.	请将设备插在电脑主USB口上进行升级。在升级前关闭杀毒软件，断开网络，禁止使用USB延长线和主机前置USB口进行升级，以保证升级流畅。更新完毕后请按:Fn+Esc组合键，然后依次按F1、F3、F5进行复位操作！

2.	如果点击“切换到BootLoader”按钮后，卡住了，显示如下界面：表明是键盘不支持命令切换到BootLoader，这种时候，使用按键组合切换到BootLoader的状态。

### 操作流程
1. 点击“切换到BootLoader”按钮切换到BootLoader状态。

2. 切换过去以后，系统识别完硬件时，点击“下载编程”按钮。

3. 下载需要时间，等待进度完成，正在下载时，右上角会有一个进度条！

## 快捷键
### 原有快捷键不变
Fn+F9 - Win key lock (with F9 being also the LED indicator)
Fn+F10 - swap Caps Lock/Left Ctrl keys (F10 LED indicator)
Fn+F11 - swap Win/Alt keys (F11 LED indicator)
Fn+F12 - 6KRO/NKRO toggle (F12 LED indicator)
Fn+Esc - toggle off/on the F9-F12 LED indicators (no LED indicator on the Esc itself)

### 背光:
Fn+0 - 关闭
Fn+8 - 所有按键统一高亮
Fn+9 - 呼吸灯
Fn+1~7 - 调整亮度
Fn+-/+ - 选择背灯模式
Fn+arrow keys - 各个背灯模式下频率快慢调整
Fn+S (hold 3 seconds) - 模式参数保存
Fn+Delete (hold 5 seconds) - 恢复默认参数

## 效果
![效果](https://github.com/imcooder/ikbc_led_light/blob/master/image/review.jpg?raw=true)