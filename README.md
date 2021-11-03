# Collections of lived2d models

## Notice

- Collected from Internet. All these stuff are from unknown source.Pls do not use them in commercial purpose. All models have been tested and worked well.

- 搜集于互联网，来源以及版权信息不明。请勿用于商业用途。所有模型都测试能够工作。

## 说明

花了一下午时间收集的萌娘们。感觉live2d的模型资源挺难找的。大部分贴图文件都被加密过无法使用。
以下是模型的预览。虽然看起来是有一点呆呆的感觉。但时间使用时，小人儿会是不是眨眨眼打个哈欠什么的的，会生动很多。比截图好看。

- chiaki_kitty![chiaki_kitty](preview/chiaki_kitty.png)
- Epsilon![Epsilon](preview/Epsilon.png)
- Kobayaxi![Kobayaxi](preview/Kobayaxi.png)
- chitose![chitose](preview/chitose.png)
- date_16![date_16](preview/date_16.png)
- hello_16![hello_16](preview/hello_16.png)
- index![index](preview/index.png)
- jin![jin](preview/jin.png)
- kanzaki![kanzaki](preview/kanzaki.png)
- kuroko![kuroko](preview/kuroko.png)
- len![len](preview/len.png)
- len_impact![len_impact](preview/len_impact.png)
- len_spqce![len_spqce](preview/len_spqce.png)
- len_swim![len_swim](preview/len_swim.png)
- mikoto![mikoto](preview/mikoto.png)
- ryoufuku![ryoufuku](preview/ryoufuku.png)
- saten![saten](preview/saten.png)
- seifuku![seifuku](preview/seifuku.png)
- shifuku![shifuku](preview/shifuku.png)
- shifuku2![shifuku2](preview/shifuku2.png)
- stl![stl](preview/stl.png)
- touma![touma](preview/touma.png)
- tsumiki![tsumiki](preview/tsumiki.png)
- uiharu![uiharu](preview/uiharu.png)
- wed_16![wed_16](preview/wed_16.png)

## how to use

use in html:

```html
<script type="text/javascript" src="/js/L2Dwidget.min.js"></script>
<script type="text/javascript" src="/js/L2Dwidget.0.min.js"></script>
<script type="text/javascript">
    L2Dwidget.init({
        model: {
            scale: 1,
            hHeadPos: 0.5,
            vHeadPos: 0.618,
            jsonPath: '/lib/live2d_models/shifuku2/shifuku2.model.json',       // xxx.model.json 的路径, 换人物需要修改这里
        },
        display: {
            superSample: 2,     // 超采样等级
            width: 120,         // canvas的宽度
            height: 300,        // canvas的高度
            position: 'left',   // 显示位置：左或右
            hOffset: 0,         // canvas水平偏移
            vOffset: 0,         // canvas垂直偏移
        },
        mobile: {
            show: false,         // 是否在移动设备上显示
            scale: 1,           // 移动设备上的缩放
            motion: true,       // 移动设备是否开启重力感应
        },
        react: {
            opacityDefault: 1,  // 默认透明度
            opacityOnHover: 1,  // 鼠标移上透明度
        },
    });
</script>
```
