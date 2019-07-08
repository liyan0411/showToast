# showtoast
 移动端toast 弹框插件。


### 插件的安装
#### NPM 
```
npm i ajshowtoast
```
#### 引入插件
```
import Vue from 'vue';
import showtoast from 'ajshowtoast';

Vue.use(showtoast);
注：由于使用了字符串模板语法渲染dom，如果有报错。
([Vue warn]: You are using the runtime-only build of Vue where the template compiler is not available. Either pre-compile the templates into render functions, or use the compiler-included build.)
请修改webpack配置：
resolve: {
	alias: {
		'vue$': 'vue/dist/vue.esm.js'
	}
}
```
#### 基本用法  
```
    接收参数：提示文本
    
    顶部：this.$toast.top('top');
    居中：this.$toast.center('center');
    底部：this.$toast.bottom('bottom');
    loading：
    打开：this.$loading('loading...');
    关闭：this.$loading.close();
```  

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
