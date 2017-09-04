# 动态组件做单页应用（无路由）

### 文件目录
```html
├─app
│  ├─modules  <!--EntryComponent.ts文件是动态加载组件的数组-->
│  │  ├─common
│  │  │  ├─header  <!--头部-->
│  │  │  └─navigation-menu  <!--左侧导航栏-->
│  │  ├─order-manage  <!--订单管理模块-->
│  │  │  └─vo
│  │  └─warehouse-manage  <!--出入库管理模块-->
│  │      ├─page
│  │      │  ├─warehouse-abnormal
│  │      │  │  └─vo
│  │      │  ├─warehouse-area-adjustment
│  │      │  │  └─vo
│  │      │  ├─warehouse-check
│  │      │  │  └─vo
│  │      │  ├─warehouse-entry-manage
│  │      │  │  └─vo
│  │      │  ├─warehouse-info
│  │      │  │  └─vo
│  │      │  └─warehouse-leave-manage
│  │      │      └─vo
│  │      └─vo
│  └─shared
│      └─services
│          └─ui
│              └─tabview <!--动态组件加载器核心代码-->   
├─assets
│  ├─css
│  │  ├─components
│  │  │  └─modal
│  │  ├─helpers
│  │  └─layout
│  ├─font-awesome-4.7.0
│  │  ├─css
│  │  ├─fonts
│  │  ├─less
│  │  └─scss
│  ├─images
│  │  └─common
│  ├─mock-data  <!--内含左侧菜单所有页面的路径信息-->
│  └─scripts
│      ├─fancybox
│      │  └─helpers
│      └─jquery
├─config
└─environments
```
### 相关文章学习

[动态组件加载器](https://angular.cn/guide/dynamic-component-loader#动态组件加载器)
[Angular 4.x 动态创建组件](https://segmentfault.com/a/1190000009175508)


