# zy-modal
微信小程序自定义modal弹窗，可带图片
# 使用方法

在json文件中
```
{
  "navigationBarTitleText": "带图片弹窗",
  "usingComponents": {
    "zy-modal": "../../component/zy-modal/zy-modal"
  }
}

```

在wxml文件中
```

<zy-modal title='图片弹窗' hidden="{{modalHidden}}" bindconfirm="modalConfirm" bindcancel="modalCandel" confirmText="确认">
  <image class="image" src="{{imageUrl}}" mode='aspectFill'></image>
  <view>江南三月雨微茫，罗伞叠烟湿幽香。</view>
  <view>夏日微醺正可人，却傍佳木趁荫凉。</view>
  <view>霜风清和更初霁，轻蹙蛾眉锁朱窗。</view>
  <view>怜卿一片相思意，犹恐流年拆鸳鸯。</view>
</zy-modal>
```

简书效果地址：[带图片弹窗效果](https://www.jianshu.com/p/a7c4d394f51a)
  
