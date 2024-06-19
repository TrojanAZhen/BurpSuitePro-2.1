## BurpSuitePro-2024.4.5

> **破解BurpSuitePro-2024.4.5版本**

- **[新版通杀loader来自 h3110w0r1d-y](https://github.com/h3110w0r1d-y/BurpLoaderKeygen/)**

**Jar包下载方式**

```
https://portswigger.net/burp/releases/download?product=pro&version=2024.4.5&type=jar
```

**不但新版可以下载，旧版本也可以！！！**

> **SHA256 && MD5**

- **burp-keygen-scz**
- - **SHA256: 74893842a782238f52f0f225c06fa744568321911fea077bc290bd9914b73402**
- - **MD5: e646b3eef03efba637e6ed794ced4114**

- **BurpLoaderKeygen_v1.17**
- - **SHA1: 3D0E27962C83C8DB2955FA79C27256442C0BCB55**
- - **MD5: A3B1B3BE59E6D3D374A2D3344213E6C7**

> **Win使用**

*一、初次使用*

  ```
  0x00 - 配置好java环境，Java21
  0x01 - 启动 BurpLoaderKeygen_v1.17.jar
    CMD：java -jar BurpLoaderKeygen_v1.17"
  0x02 - 点击Run，BurpSuite界面取消协助，同意协议
  0x03 - 随意修改 License Text
  0x04 - 把 License 复制到 BurpSuite
  0x05 - 点击 Manual activation，点击 Copy request
  0x06 - 把 Request 复制到 Activation Request
  0x07 - 把自动生成的 Activation Response 复制回 BurpSuite
  0x08 - 完成，开始使用
  ```

*二、使用过bp，已激活过license*

  ```
  0x01 - 直接加载 BurpLoaderKeygen_v1.17.jar 启动 burpsuite_pro_v2024.4.5.jar
  Powershell：java -XX:+IgnoreUnrecognizedVMOptions -javaagent:BurpLoaderKeygen_v1.17.jar=loader, --add-opens=java.desktop/javax.swing=ALL-UNNAMED --add-opens=java.base/java.lang=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED -Xmx2048m -jar burpsuite_pro_v2024.4.5.jar
  ```

**bat_script**

 ```powershell
@SET JAVA_HOME=%~dp0jre-21.0.2\
@SET Path=%JAVA_HOME%\bin;
@echo %JAVA_HOME%
@java -XX:+IgnoreUnrecognizedVMOptions -javaagent:BurpLoaderKeygen_v1.17.jar=loader, --add-opens=java.desktop/javax.swing=ALL-UNNAMED --add-opens=java.base/java.lang=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED -Xmx2048m -jar burpsuite_pro_v2024.4.5.jar
 ```

**TLS1.3和ipv4的问题**

- `-Djava.net.preferIPv4Stack=true`

> **Linux使用**

*一、初次使用*

  ```
  0x00 - 配置好java环境，Java21
  0x01 - 启动 BurpLoaderKeygen_v1.17.jar
    Terminal：/usr/lib/jvm/java-21-openjdk-amd64/bin/java -jar BurpLoaderKeygen_v1.17"
  0x02 - 点击Run，BurpSuite界面取消协助，同意协议
  0x03 - 随意修改 License Text
  0x04 - 把 License 复制到 BurpSuite
  0x05 - 点击 Manual activation，点击 Copy request
  0x06 - 把 Request 复制到 Activation Request
  0x07 - 把自动生成的 Activation Response 复制回 BurpSuite
  0x08 - 完成，开始使用
  0x09 - 可以写个执行的shell，扔到/usr/bin下面
  ```

*二、使用过bp，已激活过license*

  ```
  0x01 - 直接加载 BurpLoaderKeygen_v1.17.jar 启动 burpsuite_pro_v2024.4.5.jar
  /usr/lib/jvm/java-21-openjdk-amd64/bin/java -XX:+IgnoreUnrecognizedVMOptions -javaagent:BurpLoaderKeygen_v1.17.jar=loader, --add-opens=java.desktop/javax.swing=ALL-UNNAMED --add-opens=java.base/java.lang=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED -Xmx2048m -jar burpsuite_pro_v2024.4.5.jar
  ```

> **依旧坚持更新的大佬们**

- [1. 四哥Blog](http://scz.617.cn:8/misc/201910151519.txt)

- [2. @nszy007]()

- [3. 微信公众号: 信安前线]()

- [4. 法海之路](https://www.fahai.org/)

> **致敬**

- [1. 四哥Blog](http://scz.617.cn:8/misc/201910151519.txt)

- [2. 四哥微信公众号: 青衣十三楼飞花堂]()

- [3. 破解BurpSuite Pro 2022.9 (有变化)](https://www.52pojie.cn/thread-1687434-1-1.html)

> **破解**

```
Java 9至13，可以用javaagent的方式patch，这种在8上也能用。
Java 9至13，还可以用patch-module的方式，但8不能用。
如果Burp Pro不换注册机制，可以一直这样剁下去，改来改去就7个字节。

四哥原话在Bp破解上最大的贡献是演示了一种直接修改字节码的破解方式

2022.9版注册机制并未发生变化，仅仅是相关代码具体实现做了微调，导致class的字节码发生变化，而旧版loader模式匹配时约束条件太强，兼容性不足
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

> **Bp相关**

```
# Linux Bp激活信息保存位置
~/.java/.userPrefs/burp

# Linux Bp配置文件位置
~/.BurpSuite

# Windows Bp激活信息保存位置
注册表：HKEY_CURRENT_USER\Software\JavaSoft\Prefs\burp

# Windows Bp配置文件位置
C:\Users\%username%\AppData\Roaming\BurpSuite
```
