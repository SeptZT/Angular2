# Angular2
angular2的环境搭建文件

1、安装node v5.x.x 或更高版本以及 npm 3.x.x 或更高版本


2、新建一个目录， 如Angular2，并放入相关配置项（可在官网上复制 ）：

package.json

            用来标记出本项目所需的 npm 依赖包。

tyconfig.json

            定义了 TypeScript 编译器如何从项目源文件生成 JavaScript 代码。

typings.json

            为那些 TypeScript 编译器无法识别的库提供了额外的定义文件。

systemjs.config.js

            为模块加载器提供了该到哪里查找应用模块的信息，并注册了所有必备的依赖包。它还包括文档中后面的例子需要用到的包。


3、安装package.json中列出的依赖包

打开node转到对应的目录，如Angular2，输入：

[html] view plain copy
在CODE上查看代码片派生到我的代码片

    npm install  

（若npm install 运行结束后没有生成typings目录， 手动安装：npm run typings install）


4、在应用的根目录创建一个app子目录，并放入相关文件（可在官网上复制 ）:

app.module.ts

app.component.ts

main.ts


5、定义该应用的宿主页面，根目录下创建

index..html


6、编译并运行应用程序

[html] view plain copy
在CODE上查看代码片派生到我的代码片

    npm start  


目录结构如下，其中app下的 *.js 和 *.js.map 是npm start命令后自动生成的


官网地址：https://angular.cn/docs/ts/latest/quickstart.html