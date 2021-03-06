# anyRTC-WhiteBoard-Web

![效果图](/static/demo.png)    

> 网页白板SDK，跨平台请看 [***Android***](https://github.com/anyRTC/anyRTC-WhiteBoard-Android)、 [***iOS***](https://github.com/anyRTC/anyRTC-WhiteBoard-iOS)

## 获取开发者信息和App应用信息

前往[anyRTC 云平台](https://www.anyrtc.io)获取开发者信息，并创建一个app应用。

``` bash
# App.vue
const DEV_ID = "";//开发者ID
const APP_ID = "";//app应用ID
const APP_KEY = "";//app应用KEY
const APP_TOKEN = "";//app应用TOKEN
```

## 设置自定义数据

``` bash
# App.vue
export default {
  data () {
    return {
      pen: null,
      anyrtcId: '',//房间号，均为系统唯一，业务系统分配
      fileId: '',//文件ID，均为系统唯一，业务系统分配
      userId: '',//用户ID，均为系统唯一，业务系统分配
      nBgIndex: 1,
      nBgTotal: 1,
      backgroundList: [
        {
          board_background: 'https://www.teameeting.cn/static/images/team_section.jpg',
          board_number: 1
        }
      ]
    }
  }
}
```

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

想要了解更多请点击 [anyRTC 云平台](https://www.anyrtc.io) 或者 [更多SDK](https://github.com/anyRTC)，如需要带封装UI的demo的请联系我们。

## 技术支持 

> 加QQ技术咨询群：580477436 (一群) 554714720 (二群)  
> 欢迎加入[anyRTC社区](https://bbs.anyrtc.io) 和我们一起探讨WebRTC技术以及解决集成问题。
