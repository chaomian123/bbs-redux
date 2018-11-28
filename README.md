# bbs-redux

###Quick Start：
```
git clone https://github.com/chaomian123/bbs-redux.git
cd bbs-redux
yarn && yarn start
```
###Features
- Ducks项目文件结构
    1. component中放置通用组件
    2. action types、action creators 和reducer组成模块都放在redux/modules路径下
- 根据state的结构，拆分出app, auth, posts, comments, users, ui, index七个模块
- 利用Redux的connect函数连接组件和store， 通过Provider将store注入应用
- 使用React router v4 实现单页面应用的路由功能
- 创建了高阶组件connectRoute包裹Home，Login，使用shouldComponentUpdate方法，浅比较Router的location属性是否变化（是否处于同一个页面），决定是否更新组件，从而提高应用性能
### Architecture
![alt text](https://wx4.sinaimg.cn/mw690/77b25649gy1fxnxjiaz1hj20j216adjc.jpg "architect")

###App Shots
![alt text](https://wx1.sinaimg.cn/mw690/77b25649gy1fxnwnsgj2tj20s40ndwgs.jpg "PostList")
![alt text](https://wx3.sinaimg.cn/mw690/77b25649gy1fxnwnx4aa3j20r60ikwfn.jpg "Detail")

