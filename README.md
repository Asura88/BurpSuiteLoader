<h1 align="center">Welcome to Burp Suite loader</h1>
<p>
  <img src="https://img.shields.io/badge/release-v1.0-brightgreen" />
  <img src="https://img.shields.io/github/license/x-Ai/BurpSuiteLoader" />
</p>
<h3 align="center">有能力者请购买正版软件！ link:https://portswigger.net/burp
</h3>
<h5 align="center">本项目只是为了兴趣爱好学习交流，任何人不得将其用于非法用途以及盈利等目的，否则后果自行承担并将追究其相关责任！
</h5>
<h5 align="center">此项目可在BurpSuite不改变目前注册算法的情况下直接Patch未来更新的Burp Suite版本*
</h5>
<br>
<img src="https://github.com/x-Ai/BurpSuiteLoader/blob/master/Main.png" />

+ 分析创建: Hywell && x-Ai
+ 致谢: ***surferxyz*** && ***scz*** 二位大拿

 &ensp; &ensp;本项目起初是为了想让Burp Suite在具有HiDPI分辨率的windows机器上清楚的适配分辨率。经过测试，发现高版本的Java具有良好高分辨率的适配性。因此为了让Burp Suite可以在高分辨率上完美的运行，就参考现在常用的，经由 *scz* 大师傅修改更新loader && keygen。参考 *scz* 博文中提到的方法分析了burp-loader-keygen的Patch方法及Burp Suite的注册方法，固定了Patch方式，实现通杀。

 &ensp; &ensp;***scz*大师傅为在博客上说*为什么用"-Xbootclasspath/p:"？仅仅是最大程度重复旧版keygen套路，如果有需要可自行修改*  并且 *之所以搞成现在这种略显复杂的的局面，就是简单地想向旧版keygen的作者致敬*。
<br>
<br>
> `java version 8 - 11`

> `BurpSuite version v2020.1 - ∞`

> `java -javaagent:burp_loader.jar -jar burpsuite_pro_xxxx.jar`
<br>
