## BurpSuitePro-2020.4

> **破解BurpSuitePro-2020.4版本**

- **暂无**

> **Win使用 (当然不安装官方包也可以，直接执行-jar jar包)**

  ```
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

- `start "" "C:\Program Files (x86)\Common Files\Oracle\Java\javapath\java.exe" -noverify -Xbootclasspath/p:"C:\Program Files\BurpSuiteCommunity\burp-loader-helper.jar" -Xmx2048m -jar "C:\Program Files\BurpSuiteCommunity\burpsuite_community.jar"`

**TLS1.3和ipv4的问题**

- `Djava.net.preferIPv4Stack=true`

> **Linux使用 (当然不安装官方包也可以，直接执行-jar jar包)**

  ```
  1-在BurpSuite官网，下载Community版本的sh文件;
  2-安装"sudo bash burpsuite_community_linux_v2020_4.sh"
  3-把破解的2020.4 pro版的jar包，改名为burpsuite_community.jar，并替换软件安装目录下的burpsuite_community.jar
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

> **目前断更**

- [1. 四哥Blog](http://scz.617.cn:8/misc/201910151519.txt)

- [2. 四哥微信公众号: 青衣十三楼飞花堂]()

- [3. 52破解](https://www.52pojie.cn/thread-1038295-1-1.html)

> **某个可以第一时间更新的网站(但多数收费)**

- [Raidforums](https://raidforums.com/Forum-Cracking-Tools)

> **其他**

**2020-04-28 17:23 scz -- 来自四哥博客**

- ```
  有人提供了Burp Pro 2020.4原包，要求最低Java 9，不再支持Java 8。实际测试
  Java 8确实不行，去官网看了一下说明，官方声明也是这个意思。出于好奇心，最后
  看了一次其注册机制，没啥变化，可剁。我主要使用Java 8，并非Burp用户，能在这
  半年来坚持更新破解，算是为大伙儿尽一点小小的心意。本来，如果它还支持Java 8，
  我就继续剁下去。不想为这事再装Java 9，确实累了，另一方面也对之失去兴趣，没
  有挑战性。据我所知，很多人延着我的思路在自己剁，也剁成功了。或许你们可以等
  待新的雷锋，冥冥中另一些路见不平的老中医已经在路上。
  
  正式决定不再从事Burp破解，微信订阅号后台也不再接受Burp原包。今天有ID为火锅
  爹、Mannix的两位在微信订阅号后台提供了2020.4版原包，感谢并抱歉，未能最后一
  次提供传说中的burp-loader-keygen-2020_4.jar。
  
  今天是一个有些伤感的日子，但不再留恋，再见。
  ```

**2020-03-24 15:01 scz -- 来自四哥博客**

- ```
  迭代太快，如无绝对必要，还是用老版吧。在我发了各次迭代对应的loader之后，
  终于有人开始自力更生提供同型loader，这是好事。不好的一点是，
  某些人只提供loader，不提供原包。老中医看不惯这些SB们，只好继续1024了。
  ```

