# vue-me-player 音乐播放器

> [**快速Demo**](http://demo.metoyun.com/vue-me-player/#/)




###第一步
```
npm install vue-me-player
```
###第二步
```javascript
import MePlayer from 'vue-me-player';

Vue.component('vue-me-player',MePlayer);
```
###第三步
```html

   <me-player
        :AutoPlay="AutoPlay"
        :UserId="UserId"
        :playListId="playListId"
        :Bottom="Bottom"
        :Height="Height"
      />
```
###第四步
```javascript

       export default {
           name: 'App',
           data() {
               return {
                   AutoPlay:false,//自动播放
                   ServerUrl: "",//没有可以不填
                   UserId: 604796099,//网易云音乐用户ID,
                   playListId: 3091234621,//歌单id,
                   Bottom:2,//控制面板距离底部位置 单位：em
                   Height:50//控制面板的高度  单位：em  最大高度55em
               }
           },
   
       }
  
```
###预览图
![](http://demo.metoyun.com/vue-me-player/doc/01.png)
![](http://demo.metoyun.com/vue-me-player/doc/02.png)

"# vue-me-player" 
"# vue-me-player" 
"# vue-me-player" 
