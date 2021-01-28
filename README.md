# android_note
```txt
# 输入此命令，然后用遥控对准电视按想用的按键，bash 界面会出现此按键的 ID 识别码，记下来。选两个按键，一个用作 iptv，一个用作当贝桌面（或其他）
getevent -c 1 /dev/input/event0

# 输入命令，获取当前桌面程序
dumpsys window windows | grep -E 'mCurrentFocus|mFocusedApp'

# 启动当贝桌面
am start -n com.dangbei.tvlauncher/com.dangbei.tvlauncher.IndexActivity

# 挂载system分区读写/只读
mount -o remount,rw /system
mount -o remount,ro /system

移动魔百和cm101s adb安装第三方软件
pm install -m 0A5A0000 <apk filepath>

```
