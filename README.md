# 天气预报小程序 天气像你

## 使用指南

### 安装

```bash
git clone https://github.com/makejun168/weather-mini-program
cd weather-mini-program
yarn install
```

### 启动开发环境

```bash
yarn dev
```

### 构建生产环境

```bash
yarn build
```

### 目录结构

```
src
├── api
│   └── api.js // 接口定义
├── app.wpy // 入口文件
├── components // 组件
│   ├── comment_list.wpy // 评论
│   ├── common
│   │   ├── bottom_load_more.wpy // 底部加载
│   │   └── placeholder.wpy // 空列表
│   ├── discover.wpy // 发现组建
│   ├── filter_bar.wpy // 筛选栏组建
│   ├── filter_slider.wpy // 筛选右侧栏
│   ├── rate.wpy // 评分
│   ├── search.wpy // 搜索
│   ├── shop_grid_list.wpy // 购物商品矩阵
├── images // 图片文件夹
├── pages // 页面
│   ├── authorization.wpy // 授权
│   ├── cart.wpy // 购物车
│   ├── category.wpy // 分类
│   ├── goods_detail.wpy // 商品详情
│   ├── home.wpy // 首页
│   ├── home_detail.wpy // 首页详情
│   ├── info.wpy // 我的
│   └── search.wpy // 搜索
├── plugins
│   └── wxParse // 小程序富文本
├── styles // 样式
└── utils // 帮助文件夹
```

### feature

* master：用 `wepy new standard <project>` 初始化后得到的模版，修复了很多个 npm package 的问题。
* 1.tab-bar：创建了 tabbar
* 2.authorization：初次登陆，授权访问
* 3.info：个人页面
* 4.home-page：首页
* 5.category：分类页
* 6.home_detail：展示首页图片相关的所有商品（比较复杂）
* 7.goods_detail：商品详情（比较复杂）
* 8.cart：购物车
* 9.search：搜索功能
* develop：包含了所有的功能，最新的 branch