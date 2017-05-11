# React实战骨架

## <a name="features">&sect; 技术栈</a>
> 详情可参阅 `package.json`

* React 15.5.4
* Redux 3.6.0
* React-redux 5.0.4
* React-router-dom 4.1.1 
* Redux-saga 0.15.3
* Webpack 2.3.3
* ES6 + Babel
***

## <a name="features">&sect;  构建开发环境</a>
> 基于[vue-cli](https://github.com/vuejs/vue-cli)构建修改

## <a name="features">&sect;  precommit</a>
> 基于[standard](https://github.com/feross/standard)
## <a name="reference">&sect; 参考资料</a>
* [redux-saga中文站点](http://leonshi.com/redux-saga-in-chinese/docs/introduction/BeginnerTutorial.html)
* [react-redux](https://github.com/vue-china/react-redux-starter-kit)
* [文档风格参考kenberkeley的项目，可惜很久不更新，太老了](https://github.com/kenberkeley/react-demo)

## <a name="architecture">&sect; 项目架构</a>
### <a name="tree">⊙ 目录结构</a>
```
.
├─ build/               # 基于Vue-cli实现的Webpack构建目录
├─ dist/                # build 生成的生产环境下的项目
├─ src/                 # 源码目录
│   ├─ assets/          # images
│   ├─ components/      # 组件（COMPONENT）
│   ├─ const/           # 常量集中管理
│   ├─ containers/      # 容器
│   ├─ reducers/        # 函数因子
│   ├─ routers/         # 路由
│   ├─ saga/            # 路由视图基页（VIEW）
│   ├─ main.js          # 主入口文件
├── static/             # 放置无需经由 Webpack 处理的静态文件
├── test/               # vue-cli产出的测试目录，暂时没有处理，待更
├── index.html          # 静态模板页面，开发和build产出，都依赖它
├── .babelrc            # Babel 转码配置
├── .eslintignore       # ESLint 检查中需忽略的文件（夹）
├── .eslintrc           # ESLint 配置
├── .gitignore          # git忽悠提交
├── .postcssrc.js       # postcss配置项，vue-cli产出
├── package.json        # 很重要的东西了
```
### Instructions

Setup

```
// clone the repo
git clone https://github.com/brucecham/redux-saga.git

cd redux-saga

yarn
```

Run the demo

```
yarn start
```

build the demo

```
yarn build
```

Run tests

```
yarn test
```

update package.json

```
ncu -a
```

静态服务器

```
sts 8080
```
