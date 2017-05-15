 #这是为了H5响应式页面开发搭的一个脚手架,使用方法参考以下介绍;

 #项目CSS 单位采用rem单位;


`npm install ` 将项目需要的依赖用npm的方式安装;

`gulp dev`或者`npm start` 进行开发构建,配合`gulp liveserver` 在浏览器访问localhost:8080可实时看到代码修改后的效果;

`gulp build`或者`npm run build`进行上线打包,生成文件位于dist文件夹下;


1.在文件夹根目录下运行gulp dev,即可启动开发模式,页面的编辑和样式的书写都在src目录下进行。

2.运行gulp liveserver 可启动开发服务器插进,访问localhost:8080查看页面实时改动后的效果;

3.在src目录下进行操作时，样式单位采用measure函数,量取psd稿对应的像素后,采用measure('x'px),会实时的编译成rem单位保存到dist目录下,其他文件更改后会直接复制到dist目录下。

src目录为开发目录,dist是成品目录;

