# bh3toolRx

-修改-

用于从网络修改崩坏三的一些工具。

* EnableTouchServer .Net Core

  .Net Core平台的代理服务端，可以拦截http并修改开启触摸，引用了FiddlerCore拦截http和我自己的UnityAssetBundleTool.dll修改AssetBundle。

* FileDecryptTool

  单独的加解密的工具。包括AES和异或加解密，用于DataVersion.unity3d、Excel_output.unity3d和Setting.unity3d的加解密。

* NetPackageTool

  用于分析NetPacketV1的内容,可以从[il2cppdumper](https://github.com/Perfare/Il2CppDumper)生成的dump.cs提取出cmd_id与类的对应关系，可以从WireShark导出的文件（tcp流导出的HexDump格式）提取出protobuf序列化后的数据并转换为json格式。


* Other

  ***UnityAssetBundleTool.dll是基于[AssetStudio](https://github.com/Perfare/AssetStudio)部分代码写的AssetBundle编辑工具，性能差但是勉强能用。***



- 参考：bh3tool




<hr/>

有兴趣的可以关注【Python2048】 公众号<br/>
分享技术、灰色产业、职业规划、赚钱之道、逆向破解等趣事……

<img src="https://github.com/sheep0704/IOSIphoneHttps/blob/master/python2048.jpg" width="300" height="300">



 

