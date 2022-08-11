# mooc-ui 组件库
### 快速开始
#### 1.安装组件库
~~~bash
	npm i v-widget
~~~
#### 2.引用组件库
~~~javascript
	//全部引入
	import "v-widget/dist/css/index.css"
	import VUI from "v-widget"
	Vue.use(VUI)
	//按需引入
	import "v-widget/dist/css/demo.css"
	import {Demo} from "v-widget"
	Vue.use(Demo)
~~~