# questions_answers
这里是大家讲所提问题记录下来的地方，请将问题及后来的解决方案列出来。

# 可能用到的几个网页-sxr
* 这个网页可以在线写dart
 [dartpad](http://www.yaosansi.com/ )
 
* markdown在线编写
 [https://stackedit.io/app#](https://stackedit.io/app#)
 
* markdown语法
 [http://www.yaosansi.com](http://www.yaosansi.com/post/markdown-on-github/#4-%E9%93%BE%E6%8E%A5%E5%92%8C%E5%9B%BE%E7%89%87)

* dart 官方文档
[https://dart.cn/guides](https://dart.cn/guides)

* dart包
[https://pub.dev/](https://pub.dev/)

sever下载以后大量爆红解决办法：
1下载包
pub global activate aqueduct
aqueduct
pub get 
2修改引用路径（两种办法）
import 'package:heroes/heroes.dart';
（1）把pubspec.yaml里面的name改成heroes（推荐这钟，就不用再一个个文件改引用前面的heroes）
（2）把前面的heroes改成sever（和pubspec.yaml里面的name后面保持一致）
