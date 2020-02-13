## BurpSuitePro-2.1

**破解BurpSuitePro-2020.1版本**

**[Mega补丁下载](https://mega.nz/#!gJxwHaSQ!4NoMJwD4NXe3Vsf1C7Zt_tXsYoF0bz29pdIflVtSHbo)**

- Win使用 (当然不安装官方包也可以，直接执行-jar jar包)

  ```
  0-Pro 2020.1的加载补丁必须JDK8(只因大佬用的Java8，高版本Java换用ClassFileTransformer或其他什么技术手段来完成Patch)。。。
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

- Linux使用 (当然不安装官方包也可以，直接执行-jar jar包) 

  ```
  0-2020.1的加载补丁，不支持openjdk-11.0.5，下载一个openjdk-8先用着;
  1-在BurpSuite官网，下载Community版本的sh文件;
  2-安装"sudo bash burpsuite_community_linux_v2020_1.sh"
  3-把破解的2020.1 pro版的jar包，改名为burpsuite_community.jar，并替换软件安装目录下的burpsuite_community.jar
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

- [4. 西门吹雪](http://ximcx.cn/post-110.html)
