<h1 align="center">Welcome to Burp Suite loader</h1>
<p>
  <img src="https://img.shields.io/badge/release-v0.1-brightgreen" />
</p>

<h5 align="center">此项目可直接Patch未来更新的Burp Suite版本*
</h5>
<br>

+ 分析创建: Hywell_28 && x-Ai
+ 致谢: ***surferxyz*** && ***scz*** 二位大拿

 &ensp; &ensp; &ensp; &ensp;本项目起初是为了想让，Burp Suite在具有HiDPI分辨率的windows机器上清楚的适配分辨率。经过测试，发现高版本的Java具有良好高分辨率的适配性。因此为了让Burp Suite可以在高分辨率上完美的运行，就参考现在常用的，经由 *scz* 大师傅修改更新loader && keygen。参考 *scz* 博文中提到的方法分析了burp-loader-keygen的Patch方法及Burp Suite的注册方法，固定了Patch方式，实现通杀。

 &ensp; &ensp; &ensp; &ensp;***scz*大师傅为在博客上说*为什么用"-Xbootclasspath/p:"？仅仅是最大程度重复旧版keygen套路，如果有需要可自行修改*  并且 *之所以搞成现在这种略显复杂的的局面，就是简单地想向旧版keygen的作者致敬***。
<br>
> `java version 8 - 11`

> `java -javaagent:burp_loader.jar -jar burpsuite_pro_xxxx.jar`
