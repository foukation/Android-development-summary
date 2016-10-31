#	Android	开发资料汇总

收集这份资料的灵感来源于我的浏览器收藏夹快爆了，后来在github 上也看到了很优秀的开源库的收集资料，非常的好，但是太过于多，也不够新，所以决定自己来做一个。原始的markdowm文件已经放到github上，欢迎[下载和star](https://github.com/tonycheng93/Android-development-summary) 。这份资料我会不断的完善，也欢迎一些经验丰富的开发者可以一起来完善，直接[pull request](https://github.com/tonycheng93/Android-development-summary/pulls) 或者[issue](https://github.com/tonycheng93/Android-development-summary/issues)，我会定期筛选合并，有一些好的建议和意见随时[联系我](#联系我)，欢迎转载，谢谢收藏。
##	目录
-	[图片加载库](#图片加载库)
-	[网络请求库](#网络请求库)
-	[网络缓存](#网络缓存)


##	图片加载库

|图片库|作者|推荐理由|
|:------:|:------:|:------:|
|[Glide](https://github.com/bumptech/glide)|bumptech|支持Gif，google官方推荐的图片加载库，在google的众多App中都采用了该库|
|[Fresco](https://github.com/facebook/fresco)|Facebook|支持Gif，Facebook出品，必属精品，Fresco另辟蹊径使用Native方法来管理图片，专注解决图片内存溢出问题|
|[Picasso](https://github.com/square/picasso)|Square|开源大户Square出品，和Glide用法及其相似，Glide体积更小，JakeWharton大神所在公司|
|[Android-Universal-Image-Loader](https://github.com/nostra13/Android-Universal-Image-Loader)|nostra13|老牌图片加载库，在上述图片加载库没出来之前，使用最多的开源图片库。但是，该项目已被作者废弃不在维护，不建议使用，用来学习图片异步加载和图片管理还是极好的|

##	网络请求库

|网络库|作者|推荐理由|
|:------:|:------:|:------:|
|OkHttp|Square||
|Retrofit|Square||
|Volley|Google||

##	网络缓存

|缓存库|作者|推荐理由|
|:------:|:------:|:------:|
|[DiskLruCache](https://github.com/JakeWharton/DiskLruCache)|JakeWharton||
|[ASimpleCache](https://github.com/yangfuhai/ASimpleCache)|杨福海|afinal框架作者，国内Android大神|

