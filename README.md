# Club Chinois Home

[![npm](https://img.shields.io/npm/dw/localeval.svg)]() [![npm](https://img.shields.io/npm/v/npm.svg)]() [![Chrome Web Store](https://img.shields.io/chrome-web-store/stars/nimelepbpejjlbmoobocpfnjhihnpked.svg)]()

This project is the Home of Club Chinois, itโs mainly the reqyest time, ..

## Features ็นๆง

- **๐vue-cli่ๆๆถ๐**๏ผ่ๆๆถๅฉไฝ ๅฎ่ฃ/ๅธ่ฝฝ็ปไปถๆดๆนไพฟ๏ผ
- **๐ๅคTABๅฏผ่ช**
- ้ขๅๅฑๅฏผ่ช

## Preview ๆๆๅพ

### ไธป็้ข

![image-20210521074918054](https://cdn.jsdelivr.net/gh/LonelVino/CDN@1.4.5/ClubChinois/club-chinois-home-home.png)

### ็ปๅฝ็้ข

![image-20210521074939072](https://cdn.jsdelivr.net/gh/LonelVino/CDN@1.4.5/ClubChinois/club-chinois-home-login.png)

## Structure of The projects

```
.
โโโ API.md
โโโ api_v2
โย ย  โโโ admin.py
โย ย  โโโ apps.py
โย ย  โโโ migrations
โย ย  โโโ models.py
โย ย  โโโ tests.py
โย ย  โโโ urls.py
โย ย  โโโ views.py
โโโ build
โโโ clubChinois
โย ย  โโโ asgi.py
โย ย  โโโ settings.py
โย ย  โโโ urls.py
โย ย  โโโ wsgi.py
โโโ config
โโโ dist
โโโ index.html
โย ย  โโโ static
โย ย      โโโ css
โย ย      โโโ fonts
โย ย      โโโ img
โย ย      โโโ js
โโโ index.html
โโโ manage.py
โโโ package.json
โโโ package-lock.json
โโโ Procfile
โโโ README.md
โโโ requirements.txt
โโโ src
โย ย  โโโ api
โย ย  โย ย  โโโ cas.js
โย ย  โย ย  โโโ article.js
โย ย  โย ย  โโโ axios.js
โย ย  โย ย ............
โย ย  โโโ App.vue
โย ย  โโโ assets
โย ย  โย ย  โโโ css
โย ย  โย ย  โโโ font
โย ย  โย ย  โโโ img
โย ย  โย ย  โโโ logo.png
โย ย  โโโ components
โย ย  โย ย  โโโ Articles
โย ย  โย ย  โโโ ConversationForm
โย ย  โย ย  โโโ Modal
โย ย  โย ย  โย ย  โโโ caroulse.vue
โย ย  โย ย  โย ย  โโโ footer.vue
โย ย  โย ย  โย ย  โโโ header.vue
โย ย  โย ย  โย ย  โโโ headerWidgets
โย ย  โย ย  โย ย  โโโ OpenModal.vue
โย ย  โย ย  โย ย  โโโ SvgIcon.vue
โย ย  โย ย  โย ย  โโโ temRightlist.vue
โย ย  โย ย  ..........
โย ย  โโโ main.js
โย ย  โโโ pages
โย ย  โย ย  โโโ Aboutme.vue
โย ย  โย ย  โโโ Activities
โย ย  โย ย  โย ย  โโโ WorldWeek
โย ย  โย ย  โโโ Congulations
โย ย  โย ย  โย ย  โโโ Congulations_2.vue
โย ย  โย ย  โย ย  โโโ Congulations.vue
โย ย  โย ย  โโโ Home.vue
โย ย  โย ย  โโโ Login.vue
โย ย  โย ย  โโโ Message.vue
โย ย  โย ย  โโโ Reward.vue
โย ย  โย ย  โโโ UserInfo.vue
โย ย  โโโ router
โย ย  โโโ store
โย ย  โโโ styles
โย ย  โโโ utils
โโโ static
โโโ staticfiles
โโโ test
โย ย  โโโ e2e
โย ย  โโโ unit
โโโ vue.config.js
```

## Run ๅผๅ

```bash
    # clone the project
    git clone git@github.com:Club-Chinois/ClubChinois-Home.git

    # enter the project directory
    cd ClubChinois-Home
    
    # ๅฎ่ฃไพ่ต
    npm install
    //or 
    npm install --registry=https://registry.npm.taobao.org


    # ๆฌๅฐๅผๅ ๅผๅฏๆๅก
    npm run dev
```

## Build ๅๅธ

```bash
    # ๅๅธๆต่ฏ็ฏๅข 
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

- `็ปๅฝ/ๆณจ้`
- `ๅค็ฏๅขๅๅธ`
- `ๆ้้ช่ฏ`
- `Markdown ็ผ่พๅจ` - Article Part
- `ๅจๆrouterๆ `๏ผๆฏๆๅค็บง่ทฏ็ฑ๏ผ(a little bit bugs to be fixed)
- 404้่ฏฏ้กต้ข

## License

MIT License

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

