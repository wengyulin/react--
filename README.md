## 根据react官方脚手架create-react-app[文档](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md)修改

### 安装
    npm install   或者  cnpm install

### 启动
    热加载启动，自动扫描并编译SCSS文件
    npm start

### 发布
    npm run build

### 代码测试
    npm test
    关于官方脚手架自带的代码测试详情访问[官方介绍](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#running-tests)

### SASS

SASS使用了文档提供的基于node-sass更改的一个包，据react官方介绍,node—sass有性能和无限重复编译的bug,
这个插件的工作原理是在编译前扫描所有的sass/scss并在同目录生成同名css文件,所以在代码书写时需要直接引用同名css文件,而不能引用scss/sass文件。

### Antd

根据Antd官方文档为脚手架添加了按需加载插件

### ESLint

配置了本地ESLint检查规则(其实是抄的)检查规则为[JavaScript社区代码规范](https://standardjs.com/readme-zhcn.html)
此规则为社区公约,并不会引起编译问题,编译报错由create-react-app内部封装的ESLint进行检查并在命令行内和浏览器控制台进行报错

### React学习交流群 ： 273959805
