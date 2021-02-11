
yarn的优点 1.速度快 2支持workspace
npm 高版本 支持 workspace

yarn install 什么？
yarn install有两个使用
1.安装lerna和它的依赖
2.在根目录的node_modules里创建软链接，链向各个packages中的各个包

lerna create *** 是创建的子包还是子项目
一样的 子包就是子项目
一定要用yarn吗？
对，用npm 呢？用npm好像创建不了workspace

创建软链的能力是lerna做的吗？
yarn  install包含link功能

yarn workspace vs lerna
他们的很多功有是重复，相等的
有侧重
yarn 重点在于包管理，处理依赖，处理软链
yarn install = lerna bootstrap
lerna重点在于多个项目管理和发布

vue vue -cli babel react-router angular react .....都是是monorepo


babel团队在开发babel的时候，内部用monorepo.就独立出来的


importcost插件
npm init
npm i lerna -g
lerna init
lerna create cra-template -y
lerna create create-react-app -y
能自定义commander 参数吗？
每个子包有自己的package.json,但node_modules只有一个在根目录下？
为什么在设置版本号之前，能打印出这个值
？
你用 vsc 的命令行看输出
yarn workspace 子包名 add 依赖名
想在子包里安装依赖，yarn命令怎么写的？刚才看漏了。
私有作用域 

must1 options1 must2 options2 行不行呢？
那是形参 叫啥不重要
--help 是commander 默认的？
usage什么作用？


这段好挺好理解的
.parse方法是必须的吗？
前面都是配置
后面才是执行真正解析
理解是好理解 但是需要文档辅助查一下api啥的


JSON.strinify()为什么要加第三个参数2
格式化json
2个空格
那第二个参数null的作用是什么
替换内容


spawn是干啥的？
创建子进程
谢谢
这块是啥意思？开启子进程加载依赖？
难道 node 自带的 spawn 不跨子进程？
是的
说错了，不跨平台
跨平台
她在他在ヾ:跨平台


也可以道自己的git上拉取自定义模版
react-script  就是。bin目录文件 吧？
没有template？
chdir  就是改变  cwd  ，有什么影响
template 应该在src 下
改变了 cwd 有什么作用
就是进入到你的项目中安装
卡了
有些是共用的，有些单独的
chalk应该放在根里
package1 
package2 commander
package3 
不是说node_module多个项目共用吗？为什么还要再自己项目下面安装
react react-dom cra-template react-scripts

学习create-react-app 
主要有三块内容 
1.创建项目的流程 讲完了
2.react-scripts里面的命令 init build start 一共五个命令
3.就是cra-template里面的webpack配置最佳实践 详细配置



