# -
前端一些链接balabala

[mpvue官方文档](http://mpvue.com/)

[vue官方文档](https://cn.vuejs.org/v2/guide/)


环境配置、如何创建一个在框架下的小程序/和vscode连接  
[使用mpvue开发微信小程序（一）](https://cloud.tencent.com/developer/article/1191052)  
[环境配置比较详细](https://www.anyanf.com/post/html/quick-start-wx-mpvue/)  

NPM（node package manager),通常称为node包管理器，主要功能就是管理node包，包括：安装、卸载、更新、查看、搜索、发布等。

要记得每次要先在cmd中  
**cd firstapp  
npm run dev**  
才能改动代码并且实时查看  

[vue.js菜鸟教程](https://www.runoob.com/vue2/vue-start.html)  
[css 菜鸟教程](https://www.runoob.com/css/)
[css3菜鸟教程](https://www.runoob.com/css3/css3-tutorial.html)
[css字体](https://blog.csdn.net/qq_31603575/article/details/80202997)

src是我们要编辑的代码页，在pages中新建页面进行编译，每个页面要形成单独的子文件夹，有xx.vue,main.js(形成vue实例),main.json(自定义页面配置)  
dist是程序根据我们在src中写的html/web代码自动生成的小程序代码  

插入图片：  
<template>
  <div class="container">
    <img :src="toc_icon">
  </div>
</template>

<script>
export default {
  data () {
    return {
      toc_icon: '/static/images/toc.png'
    }
  }
}
</script>  

注意：路径要用/而不是\或\\

**【Vue报错】**  
1.关于 The template root requires exactly one element 报错的解决方案  
Vue只允许模板里存在一个根节点。在 <template> 中添加一个 <div>标签，之后所有的组件全部加在 <div>即可解决。
