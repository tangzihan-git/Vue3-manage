### 项目介绍

本项目基于 Vue3 + TypeScript + Vite + Element-plus + Pinna + Echarts 实现的通用后台管理系统，可以作为管理系统模板使用，功能强大支持主题切换、JSON表格、页面缓存、常用指令（防抖、节流）等。

### 在线预览 👀

- Link：https://admin.spicyboy.cn

### 代码仓库

给个start呗
- GitHub：https://github.com/tangzihan-git/Vue3-manage


### 主要功能介绍

- 使用 Vue3 + TypeScript 开发
- 采用 Vite 作为构建工具配置了TSX、跨域、Gzip、去除console等
- 对Axios进行二次封装，实现了请求拦截、token无感刷新、取消重复请求等
- 状态管理采用Pinia，支持持久化配置
- 支持主题配置，如布局切换、颜色切换、全局管理组件大小
- 支持i18n国际化
- VueRouter方面有路由拦截、权限相关、动态路由、路由懒加载
- 内置常用指令权限指令、防抖指令、节流指令、复制指令
- 支持代码规范（不需要可关闭）采用 ESLint、Stylelint校验
- 使用 husky、lint-staged、commitlint、czg、cz-git 规范提交信息

### 如何使用

**第一步**

```text
git clone https://github.com/tangzihan-git/Vue3-manage.git
```

**第二步**

```text
cd Vue3-manage
npm i
```

**第三步**


```text
npm run dev
```

### 系统环境说明
系统支持开发、测试、生产三个环境，对应的环境变量在项目根目录
.env.development 开发环境
.env.production 生产环境
.env.test 测试环境

### 代码规范

```text
# eslint 检测代码
npm run lint:eslint

# prettier 格式化代码
npm run lint:prettier

# stylelint 格式化样式
npm run lint:stylelint
```



### 项目截图 



### 项目架构

```text
Vue3-manage
├─ .husky                 # husky 配置文件
├─ .vscode                # VSCode 推荐配置
├─ build                  # Vite 配置项
├─ public                 # 静态资源文件（该文件夹不会被打包）
├─ src
│  ├─ api                 # API 接口管理
│  ├─ assets              # 静态资源文件
│  ├─ components          # 全局组件
│  ├─ config              # 全局配置项
│  ├─ directives          # 全局指令文件
│  ├─ enums               # 项目常用枚举
│  ├─ hooks               # 常用 Hooks 封装
│  ├─ languages           # 语言国际化 i18n
│  ├─ layouts             # 框架布局模块
│  ├─ routers             # 路由管理
│  ├─ stores              # pinia store
│  ├─ styles              # 全局样式文件
│  ├─ typings             # 全局 ts 声明
│  ├─ utils               # 常用工具库
│  ├─ views               # 项目所有页面
│  ├─ App.vue             # 项目主组件
│  ├─ main.ts             # 项目入口文件
│  └─ vite-env.d.ts       # 指定 ts 识别 vue
├─ .editorconfig          # 统一不同编辑器的编码风格
├─ .env                   # vite 常用配置
├─ .env.development       # 开发环境配置
├─ .env.production        # 生产环境配置
├─ .env.test              # 测试环境配置
├─ .eslintignore          # 忽略 Eslint 校验
├─ .eslintrc.cjs          # Eslint 校验配置文件
├─ .gitignore             # 忽略 git 提交
├─ .prettierignore        # 忽略 Prettier 格式化
├─ .prettierrc.cjs        # Prettier 格式化配置
├─ .stylelintignore       # 忽略 stylelint 格式化
├─ .stylelintrc.cjs       # stylelint 样式格式化配置
├─ CHANGELOG.md           # 项目更新日志
├─ commitlint.config.cjs  # git 提交规范配置
├─ index.html             # 入口 html
├─ LICENSE                # 开源协议文件
├─ lint-staged.config.cjs # lint-staged 配置文件
├─ package-lock.json      # 依赖包包版本锁
├─ package.json           # 依赖包管理
├─ postcss.config.cjs     # postcss 配置
├─ README.md              # README 介绍
├─ tsconfig.json          # typescript 全局配置
└─ vite.config.ts         # vite 全局配置文件
```


### 项目后台接口 🧩

项目后台接口完全采用 Mock 数据，感谢以下 Mock 平台支持：

- FastMock： https://www.fastmock.site
- EasyMock：https://mock.mengxuegu.com



### 捐赠 

如果你正在使用这个项目或者喜欢这个项目的，可以通过以下方式支持我：

- Star、Fork、Watch 一键三连 🚀
- 通过微信、支付宝一次性捐款 ❤

|                                        微信                                        |                                       支付宝                                       |
| :--------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------: |
| <img src="https://i.imgtg.com/2023/01/16/QRzBX.png" alt="Alipay QRcode" width=170> | <img src="https://i.imgtg.com/2023/01/16/QRFZt.png" alt="Wechat QRcode" width=170> |
