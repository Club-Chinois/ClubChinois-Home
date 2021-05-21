# Club Chinois Home

[![npm](https://img.shields.io/npm/dw/localeval.svg)]() [![npm](https://img.shields.io/npm/v/npm.svg)]() [![Chrome Web Store](https://img.shields.io/chrome-web-store/stars/nimelepbpejjlbmoobocpfnjhihnpked.svg)]()

This project is the Home of Club Chinois, it’s mainly the reqyest time, ..

## Features 特性

- **👍vue-cli脚手架👍**（脚手架助你安装/卸载组件更方便）
- **👉多TAB导航**
- 面包屑导航

## Preview 效果图

### 主界面

![image-20210521074918054](https://cdn.jsdelivr.net/gh/LonelVino/CDN@1.4.5/ClubChinois/club-chinois-home-home.png)

### 登录界面

![image-20210521074939072](https://cdn.jsdelivr.net/gh/LonelVino/CDN@1.4.5/ClubChinois/club-chinois-home-login.png)

## Structure of The projects

```
.
├── API.md
├── api_v2
│   ├── admin.py
│   ├── apps.py
│   ├── migrations
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── build
├── clubChinois
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── config
├── dist
├── index.html
│   └── static
│       ├── css
│       ├── fonts
│       ├── img
│       └── js
├── index.html
├── manage.py
├── package.json
├── package-lock.json
├── Procfile
├── README.md
├── requirements.txt
├── src
│   ├── api
│   │   ├── cas.js
│   │   ├── article.js
│   │   ├── axios.js
│   │  ............
│   ├── App.vue
│   ├── assets
│   │   ├── css
│   │   ├── font
│   │   ├── img
│   │   └── logo.png
│   ├── components
│   │   ├── Articles
│   │   ├── ConversationForm
│   │   ├── Modal
│   │   │   ├── caroulse.vue
│   │   │   ├── footer.vue
│   │   │   ├── header.vue
│   │   │   ├── headerWidgets
│   │   │   ├── OpenModal.vue
│   │   │   ├── SvgIcon.vue
│   │   │   └── temRightlist.vue
│   │   ..........
│   ├── main.js
│   ├── pages
│   │   ├── Aboutme.vue
│   │   ├── Activities
│   │   │   └── WorldWeek
│   │   ├── Congulations
│   │   │   ├── Congulations_2.vue
│   │   │   └── Congulations.vue
│   │   ├── Home.vue
│   │   ├── Login.vue
│   │   ├── Message.vue
│   │   ├── Reward.vue
│   │   └── UserInfo.vue
│   ├── router
│   ├── store
│   ├── styles
│   └── utils
├── static
├── staticfiles
├── test
│   ├── e2e
│   └── unit
├── vue.config.js
```

## Run 开发

```bash
    # clone the project
    git clone git@github.com:Club-Chinois/ClubChinois-Home.git

    # enter the project directory
    cd ClubChinois-Home
    
    # 安装依赖
    npm install
    //or 
    npm install --registry=https://registry.npm.taobao.org


    # 本地开发 开启服务
    npm run dev
```

## Build 发布

```bash
    # 发布测试环境 
    npm run build
```

Or:

```bash
# build for test environment
npm run build:stage

# build for production environment
npm run build:prod

```

## Unit Test

```bash
# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

## Advanced

```bash
# preview the release environment effect
npm run preview

# preview the release environment effect + static resource analysis
npm run preview -- --report

# code format check
npm run lint

# code format check and auto fix
npm run lint -- --fix
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

## TODO List

- `登录/注销`
- `多环境发布`
- `权限验证`
- `Markdown 编辑器` - Article Part
- `动态router栏`（支持多级路由）(a little bit bugs to be fixed)
- 404错误页面

## License

MIT License

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

