# Xcode_DeviceSupport
Xcode Device Support Image Files


##问题：有时候我们更新了iOS设备系统版本，但Xcode没有更新。Xcode包很大（>4G），但时间要紧有需要马上用到升级过系统的iOS设备，怎么办？

##解答：Xcode支持多个iOS设备，但每个iOS设备支持都需要DeviceSupport系统镜像，iOS系统镜像路径/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport。把对应iOS系统版本的镜像拷贝到以上目录，重启Xcode，等着Xcode copy设备文件完成即可。