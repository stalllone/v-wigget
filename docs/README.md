# 快速开始

### 安装组件库

```bash
npm install v-widget
```

### 引用组件库
> 在 main.js 中引入组件库

```javascript
/* 全局引入 */
import "v-widget/dist/css/index.css"
import VUI from "v-widget"
Vue.use(VUI)

/* 按需引入 */
import "v-widget/dist/css/demo.css"
import { Demo } from "v-widget"
Vue.use(Demo)
```
