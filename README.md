### zlLoading
> loading 动态加载
###### 使用方法
> js

```
import 'ZlLoading' from 'zl-loading'
Vue.use(ZlLoading)

this.$loading.show('circle',{text:'加载中...­',type:'wave'})
参数1 目前可选loading样式:  circle, accordion, double-circle, heart, rotate-circle, scale-circle
参数2 目前可选文字: {text: 自己定义的 text值, type: 目前只支持 wave},可以不传，使用默认值
```