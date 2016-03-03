# gulp-sass-compile
基于gulp及gulp-sass的sass实时编译工具，实时将：sass/scss文件编译为css文件(生成的css文件与scss/sass文件位于同一个目录下)。

## 工具特点
1、基于node-sass（非node-ruby-sass）第三方Node.js包实现，无需安装Ruby；  
2、实时编译；  
3、不需要手动指定需要编译的文件目录，根据项目结构特点自动生成编译目录，自动寻址；  
4、css代码格式化&美化；  
5、自动化样式prefix添加；  
6、支持sass/scss添加注释(// | /***/均支持)，编译后的css文件会自动去除掉；  
7、编译成功/失败弹框提示（成功提示可手动配置关闭掉，错误提示带有声音，且会在控制台打印出详细的错误信息）；  

## 用法
全局安装gulp：`npm install -g gulp`，然后只需要在终端命令行项目根目录下执行gulp命令即可。
