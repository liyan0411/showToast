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
