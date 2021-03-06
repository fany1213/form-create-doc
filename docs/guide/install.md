### 安装



#### CDN 引入

目前可以通过 [unpkg.com/form-create](https://unpkg.com/form-create/) 获取到最新版本的资源，在页面上引入 js 即可开始使用。

iviewUI

```html
<!-- import Vue.js -->
<script src="//vuejs.org/js/vue.min.js"></script>
<!-- import stylesheet -->
<link rel="stylesheet" href="//unpkg.com/iview/dist/styles/iview.css">
<!-- import iView -->
<script src="//unpkg.com/iview/dist/iview.min.js"></script>
<!-- import form-create -->
<script src="//unpkg.com/form-create/dist/form-create.min.js"></script>

```

elementUI

```html
<!-- import Vue.js -->
<script src="//vuejs.org/js/vue.min.js"></script>
<!-- 引入样式 -->
<link rel="stylesheet" href="https://unpkg.com/element-ui/lib/theme-chalk/index.css">
<!-- 引入组件库 -->
<script src="https://unpkg.com/element-ui/lib/index.js"></script>
<!-- import form-create -->
<script src="//unpkg.com/form-create/dist/form-create.elm.min.js"></script>
```





#### NPM 

**安装**

推荐使用 npm 的方式安装，它能更好地和 [webpack](https://webpack.js.org/) 打包工具配合使用。

```shell
npm i form-create
```

**引入**

iviewUI

```js
import formCreate from 'form-create'
```

elementUI

```js
import formCreate from 'form-create/element'
```



#### 图例

![form-create 图例](https://raw.githubusercontent.com/xaboy/form-create/dev/images/sample110.jpg?1)



#### 示例

通过 CDN 可以快速使用 iView 写出一个示例，您可以复制下面代码或[在线预览](http://fiddle.jshell.net/xaboy/j2zg6et0/show)。

<ClientOnly>

<iframe width="100%" height="600" src="//jsfiddle.net/xaboy/j2zg6et0/3/embedded/html,result/" allowfullscreen="allowfullscreen" allowpaymentrequest frameborder="0"></iframe>

</ClientOnly>