# tabs

tab动态字体缩放，动态滑块缩放效果

## 使用方式

**在index.vue中**  

~~~
import clTabs from "@/components/cl-tabs/cl-tabs";
components:{clTabs},
~~~

## OBJECT参数说明

| 参数 | 类型 | 默认值 | 说明 |
| --- | --- | --- | --- |
| tabBars | Array | [] | 标题 |
| tabIndex | Number | -1 | 当前tab索引 |
| scale | Number | 1 | 放大倍数 |
| type | String | default | fill包含 float上浮 hang悬空 |
| sliderColor | String | '#ff461f' | 滑块颜色 |
| textColor | String | 'black' | 所有字体颜色 |
| selectColor | String | 'black' | 选中字体颜色 |
| sliderMargin | Number | 20 | 延长滑块长度 px |
| center | Boolean | false | 居中 |

## 如果觉得插件不错，麻烦给个好评
