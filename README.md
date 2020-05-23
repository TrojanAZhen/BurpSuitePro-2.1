## BurpSuitePro-2020.4.1

> **破解BurpSuitePro-2020.4.1版本**

- **[Mega - Pro jar包](https://mega.nz/file/PJ0H3JIL#H7Lc0spRbNd3k8W6MQz0dBivQGKlO2MM3UuNbfK5kZ4)**

- **[Zippy - Pro jar包](https://www89.zippyshare.com/v/vtwIvMFu/file.html)**

- **[Mega - zip包](https://mega.nz/file/SVUFSQgQ#osze1oItI_MBXNSIFoF3psYpHR3Rl6OCPfdo2Jc0jRc)** *解压密码：mrxn.net*

- **[微云 - zip包](https://share.weiyun.com/i0u9iepi)**

- **[百度云 - zip包](https://pan.baidu.com/s/1KQMBtxZxAxXRZ55aB81f4w)** *提取码：miku*

> **Win使用 (当然不安装官方包也可以，直接执行-jar jar包)**

  ```
  0-x-Ai大佬的loader不带keygen，激活keygen得用旧版本，支持Java9-Java13
  1-在BurpSuite官网，下载Community版本的安装包
  2-把pro版的jar包，改名为burpsuite_community.jar，并替换软件安装目录下的burpsuite_community.jar
  3-启动旧版loader(loader用java 13.0.2无任何问题，如果之前已经激活过，直接进行第4步即可)
  Powershell：java -jar "C:\Program Files\BurpSuiteCommunity\2020_2_1-burp-loader-helper.jar"

  4-打开burpsuite_community.jar
  Powershell：java -noverify -javaagent:"C:\Program Files\BurpSuiteCommunity\burp-loader-helper.jar" -Xmx2048m -jar "C:\Program Files\BurpSuiteCommunity\burpsuite_community.jar"
  
  5-取消协助，同意协议
  6-随意修改burp-loader-helper的License Text
  7-把License复制到BurpSuite
  8-点击Manual activation，点击Copy request
  9-把Request复制到burp-loader-helper的Activation Request
  10-把自动生成的Activation Response复制回BurpSuite
  11-完成，开始使用
  12-持久启动必须先加载loader，不然依旧要license key
  ```

**bat_script**

- `start "" "C:\Program Files (x86)\Common Files\Oracle\Java\javapath\java.exe" -noverify -javaagent:"C:\Program Files\BurpSuiteCommunity\burp-loader-helper.jar" -Xmx2048m -jar "C:\Program Files\BurpSuiteCommunity\burpsuite_community.jar"`

**TLS1.3和ipv4的问题**

- `-Djava.net.preferIPv4Stack=true`

> **Linux使用 (当然不安装官方包也可以，直接执行-jar jar包)**

  ```
  0-x-Ai大佬的loader不带keygen，激活keygen得用旧版本，支持Java9-Java13
  1-在BurpSuite官网，下载Community版本的sh文件;
  2-安装"sudo bash burpsuite_community_linux_v2020_4_1.sh"
  3-把pro版的jar包，改名为burpsuite_community.jar，并替换软件安装目录下的burpsuite_community.jar
  4-启动旧版loader(loader用java 13.0.2无任何问题，如果之前已经激活过，直接进行第5步即可)
  /usr/lib/jvm/java-13-openjdk-amd64/bin/java -jar 2020_2_1-burp-loader-helper.jar

  5-启动BurpSuiteCommunity
  /usr/lib/jvm/java-13-openjdk-amd64/bin/java -Dfile.encoding=utf-8 -noverify -javaagent:/opt/BurpSuiteCommunity/burp-loader-helper.jar -Xmx2048m -jar /opt/BurpSuiteCommunity/burpsuite_community.jar

  6-取消协助，同意协议
  7-随意修改burp-loader-helper的License Text
  8-把License复制到BurpSuite
  9-点击Manual activation，点击Copy request
  10-把Request复制到burp-loader-helper的Activation Request
  11-把自动生成的Activation Response复制回BurpSuite
  12-完成，开始使用
  13-持久启动必须先加载loader，不然依旧要license key
  14-可以写个执行的shell，扔到/usr/bin下面
  ```
> **依旧坚持更新的大佬们**

- [1. x-Ai](https://github.com/x-Ai/BurpSuiteLoader)

- [2. 微信公众号: 姑娘 别来无恙]()

- [3. Mrxn's Blog](https://mrxn.net/)

- [4. 小晨曦](https://xcxmiku.com/)

> **致敬**

- [1. 四哥Blog](http://scz.617.cn:8/misc/201910151519.txt)

- [2. 四哥微信公众号: 青衣十三楼飞花堂]()

> **某个可以第一时间更新的网站(但多数收费)**

- [Raidforums](https://raidforums.com/Forum-Cracking-Tools)

> **破解**

```
Java 9至13，可以用javaagent的方式patch，这种在8上也能用。
Java 9至13，还可以用patch-module的方式，但8不能用。
如果Burp Pro不换注册机制，可以一直这样剁下去，改来改去就7个字节。
有VirusTotal企业帐号的可以从VT下原包。

四哥原话在Bp破解上最大的贡献是演示了一种直接修改字节码的破解方式
```

**反编译jar For Linux**

```
-classpath <路径>            指定查找用户类文件和注释处理程序的位置

-d <目录>                    指定放置生成的类文件的位置

cd  burp-loader-keygen.jar.src

javac -classpath burp-loader-keygen.jar -d . enjoy/reversing/me/KeygenDialog.java
```

![](https://github.com/jas502n/BurpSuite_Pro_v1.7.37/blob/master/javac.jpg)

![](https://github.com/jas502n/BurpSuite_Pro_v1.7.37/raw/master/JD-GUI.jpg)

[参考jas502n](https://github.com/jas502n/BurpSuite_Pro_v1.7.37/blob/master/README.md)

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

> **某些错误**

```
Burp Suite 2020.4.1
    BUG:存在消息编辑器中文本重叠的问题【致命，该问题出现在部分用户处】

Burp Suite 2020.4
    BUG:存在消息编辑器中文本重叠的问题【致命，这个版本直接舍弃】

Burp Suite 2020.2.1
    BUG:Burp Repeater中发送的每个请求的响应时间不可以正确显示【影响延时注入判定，没有响应时间，很影响使用】

Burp Suite 2020.2
    特征：文本显示正常，输入中文正常，响应时间显示正常

Burp Suite 2020.1
    BUG:输入中文异常,中文乱码
```
