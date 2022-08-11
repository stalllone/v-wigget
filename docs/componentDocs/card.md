# Card
卡片组件

### 示例:
<m-card imgSrc="/v-wigget//card3.jpg" summary="0到1快速构建自己的后台管理系统"></m-card>

### 代码
```html
<m-card imgSrc="/card3.jpg" summary="0到1快速构建自己的后台管理系统"></m-card>
```

### Attributes
| 参数 | 说明 | 类型 | 是否必要 | 默认值 |
| --- |  --- | ---  | -------- | ----- |
| width | 卡片宽度 |Number |false | - |
| imgSrc | 图片地址 |String | true | - |
| imgHeight | 图片高度 | Number | false | - |
| summary | 卡片概要 | String/Slot | false | - |
| footer | 	卡片底部 | Slot | false | - |