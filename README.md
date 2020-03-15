## BurpSuitePro-2020.2

> **破解BurpSuitePro-2020.2版本**

- **[Mega补丁下载](https://mega.nz/#!oMhwBYaZ!4l4OpE0ZiAwTqttzzPWItytOGumA6N-0b8MNY_AX4Vo)**

- **[百度云下载](https://pan.baidu.com/s/1EXfiqdBB6Kssf58COlfG0Q)** *提取码：jo4n*

- **[52爱盘下载](https://down.52pojie.cn/Tools/Network_Analyzer/)**

- ~~试过上传蓝奏云，可惜最后一个压缩包死活传不上去(普通用户100m上传限制)~~

- **[115网盘](https://115.com/s/sw3k0t736qr)** *访问码：ue14*

> **Win使用 (当然不安装官方包也可以，直接执行-jar jar包)**

  ```
  0-Pro 2020.2的加载补丁必须JDK8(只因大佬用的Java8，高版本Java换用ClassFileTransformer或其他什么技术手段来完成Patch)。。。
  1-在BurpSuite官网，下载Community版本的安装包;
  2-把破解的pro版的jar包，改名为burpsuite_community.jar，并替换软件安装目录下的burpsuite_community.jar
  3-打开burp-loader-helper.jar
  Powershell：java -jar "C:\Program Files\BurpSuiteCommunity\burp-loader-helper.jar"
  
  4-打开burpsuite_community.jar
  java -noverify -Xbootclasspath/p:"C:\Program Files\BurpSuiteCommunity\burp-loader-helper.jar" -Xmx2048m -jar "C:\Program Files\BurpSuiteCommunity\burpsuite_community.jar"
  
  5-取消协助，同意协议
  6-随意修改burp-loader-keygen的License Text
  7-把License复制到BurpSuite
  8-点击Manual activation，点击Copy request
  9-把Request复制到burp-loader-keygen的Activation Request
  10-把自动生成的Activation Response复制回BurpSuite
  11-完成，开始使用
  12-持久启动必须先加载keygen，不然依旧要license key
  ```

  **bat_Code**

  `start "" "C:\Program Files (x86)\Common Files\Oracle\Java\javapath\java.exe" -noverify -Xbootclasspath/p:"C:\Program Files\BurpSuiteCommunity\burp-loader-helper.jar" -Xmx2048m -jar "C:\Program Files\BurpSuiteCommunity\burpsuite_community.jar"`

  **TLS1.3和ipv4的问题**

  `Djava.net.preferIPv4Stack=true`

> **Linux使用 (当然不安装官方包也可以，直接执行-jar jar包)**

  ```
  0-2020.2的加载补丁，不支持openjdk-11.0.5，下载一个openjdk-8先用着;
  1-在BurpSuite官网，下载Community版本的sh文件;
  2-安装"sudo bash burpsuite_community_linux_v2020_2.sh"
  3-把破解的2020.2 pro版的jar包，改名为burpsuite_community.jar，并替换软件安装目录下的burpsuite_community.jar
  4-启动burp-loader-helper.jar
  /usr/lib/jvm/java-8-openjdk-amd64/bin/java -jar burp-loader-helper.jar
  
  5-启动BurpSuiteCommunity
  /usr/lib/jvm/java-8-openjdk-amd64/bin/java -noverify -Xbootclasspath/p:/opt/BurpSuiteCommunity/burp-loader-helper.jar -Xmx2048m -jar /opt/BurpSuiteCommunity/burpsuite_community.jar

  6-取消协助，同意协议
  7-随意修改burp-loader-keygen的License Text
  8-把License复制到BurpSuite
  9-点击Manual activation，点击Copy request
  10-把Request复制到burp-loader-keygen的Activation Request
  11-把自动生成的Activation Response复制回BurpSuite
  12-完成，开始使用
  13-可以写个执行的shell，扔到/usr/bin下面
  ```

> 长期更新

- [1. 四哥Blog](http://scz.617.cn:8/misc/201910151519.txt)

- [2. 四哥微信公众号: 青衣十三楼飞花堂]()

- [3. 52破解](https://www.52pojie.cn/thread-1038295-1-1.html)

> **其他**

- **2020-03-05 12:56 scz -- 来自四哥博客**

- ```
  有朋友提供了百度网盘下载链接，但我没推荐，因为百度网盘是我见过的最垃圾的网
  盘。都2020年了，一个SVIP帐号在下载了1.5G之后被限速至27B/s，你没有看错单位，
  还不如普通帐号的18KB/s。更重要的是，这些百度网盘链接很少是永久的，一般是7
  天有效期，既然如此，不如不推荐。
  
  本文发出去大概30分钟后，很可能就有一大批其他公众号或什么垃圾下载网站号称第
  一时刻提供2020.2版破解及汉化，俨然内幕人士，更大可能会要求你关注它或注册或
  积分等等，绝口不提其实这东西已经可以自由无障碍下载获取。总之你将看到这些SB
  们轮番出来天秀。作为长期像牛皮癣一样出现在电线杆上的老中医，我郑重奉劝年少
  无知得病的同学们，这事，只能找老中医治，我们老中医的口号是：一针就灵。
  ```
