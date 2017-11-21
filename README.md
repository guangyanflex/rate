# Rate
a simple vue rate component /一个简单的vue-rate评分组件
# 用法
### 直接下载rate.vue 到项目的任意目录（建议放在components目录下）
### 然后在需要引入的页面使用

#### js代码
     //注意：这里的'./components/rate'要替换成你实际存放的位置
     import rate from './components/rate'   

#### HTML简单代码
     //什么参数都不加，全部使用默认参数 
     //星星数：五颗
     //尺寸：25px
     //评分：5分
     //背景颜色：灰色
     //前景颜色：橙色
     //写入权限：可写
     <rate/>

#### 其他用法
     <rate :value="3" :size="30" :length="6" frontColor="#f00" backColor="#ccc" :writeable="false"/>

#### 参数说明
