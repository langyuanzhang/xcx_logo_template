# xcx_logo_template
小程序公司logo模板


```html
<import src="../gxyy/gxyy.wxml" />

<template is="msgItem" data="" />
```

gxyy.wxml

```html
<template name="msgItem">
  <view class='template'>
    <image src='/images/youyunlogo.png'></image>
    <view class='text'>有限公司技术支持</view>
  </view>
</template>
```

wxss

```css
.template{
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  font-size: 28rpx;
  color:#888;
  height: 180rpx;
  margin-top: 100rpx;
}
.template image{
  width: 75rpx;
  height: 75rpx;
}
.template .text{
  height:60rpx;
  line-height:60rpx;
}
```
