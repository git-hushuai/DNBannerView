# DNBannerView
原生实现的图片轮播组件：

+ 支持代码和xib创建;
+ 使用UIScrollView内嵌两个UIImageView实现图片轮播展示;
+ 支持本地以及网络图片，网络图片支持占位机制;
+ 支持gif;
+ 支持delegate以及Block回调;
+ 图片切换支持滚动以及淡入淡出模式;
+ 支持PageControlPosition样式可选;

	>  位置：隐藏、中上、左下、中下、右下
	>  可自定义分页控件指示器当前页以及非当前页时的图片和颜色
+ 支持添加图片文字描述;
+ 支持图片缓存、缓存清除;

```
简单使用只需要设置imageArray即可
/**
 *  轮播的图片数组，可以是本地图片（UIImage，不能是图片名称），也可以是网络路径
 *  支持网络gif图片，本地gif需做处理后传入
 */
@property (nonatomic, strong) NSArray *imageArray;

```

[](https://github.com/git-hushuai/DNBannerView/blob/master/QQ20180813-133626-HD.mp4)