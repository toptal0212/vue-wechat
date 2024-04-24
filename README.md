# vue-wechat
  Developing a WeChat app using vue.js.

#### The main intention is to practice new technologies through personal projects, discover issues in business, accumulate experience, and exchange ideas with others.

  Online address: [vue-wechat.github.io](https://vue-wechat.github.io)

  Project address: [useryangtao/vue-wechat](https://github.com/useryangtao/vue-wechat)

  github.io loads a bit slow, it is recommended to clone and debug locally.


### Installation

``` bash
# install dependencies
cnpm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

```
### Technology Stack
  vue-wechat mainly utilizes Vue.js to implement the WeChat app and many details.

  This demo uses the following technologies for implementation:
  
  - vue
  - vuex
  - vue-cli
  - vue-router
  - vue-touch
  - vue-animated-list
  - weui
  - zepto
  - fastclick

#### Some Highlights

  Transition animations for new page navigation mimic the page switching style of the iOS system, achieved through combining router-view and transition features.

  Handling left swipe action on message list items using vuex (getters, actions) for real-time data processing.

  Animation transitions between (voice/text) dialogue box components, along with tap event registration for holding to speak effect.

  Additional interaction details and animations:
   - CSS3 animation for scan feature;
   - Message list item deletion with animation using vue-animated-list;
   - Animation for displaying/hiding the "+" button in the message page;
  
  Dragging down to show complete cover in the friend circle section.
  
  The listview section also utilizes the structure of weui.
  
  All small icons are implemented using iconfont to reduce image requests.
  

### Mobile Preview (QR)

  ![](./src/assets/images/readme/qr-vue-wechat.png)
  
  If the QR code appears blank when scanned with WeChat, please click the upper right corner -> Open in Browser. 
  Initial loading may be slow, please be patient.


### Basic Operations

  Home Page

  ![](./src/assets/images/readme/view-chat-contact.png)![](./src/assets/images/readme/view-chat.png)

  Page switching with animation transition
  (Mimicking iOS system switch style: when opening the next page, the current page shifts left by -30%; when closing the current page, the previous page shifts left from -30% to 0%)

  ![](./src/assets/images/readme/view-wechat-animation.gif)

  Message list (unread/read) operations and deletion

  ![](./src/assets/images/readme/view-wechat-chat.gif)

  Press and hold to speak, release to end effect

  ![](./src/assets/images/readme/tap-say.png)

  Discovery - Moments

  ![](./src/assets/images/readme/view-wechat-find-albums-friends.gif)

  Discovery - Scan

  ![](./src/assets/images/readme/view-wechat-find-sao-yi-sao.gif)

  Iconfont Icons

#### To reduce image loading, icons are implemented using iconfont

  ![](./src/assets/images/readme/font.png)

### Add to Home Screen

  ![](./src/assets/images/readme/add-to-screen.png)



### Development Conventions
  ``` bash
  All .vue component names are uniformly named with hyphens.
  Classes starting with an underscore (_) in CSS are common classes.
  Properties starting with an underscore (_) in JavaScript are private.
  All events are named with hyphens.
  Elements contained within the template tag of all components (.vue) must start with component-xx.
  All states are uniformly named with underscores.
  All actions are uniformly named with underscores.
  ```


### References

  [Vue-cnodejs](https://github.com/shinygang/Vue-cnodejs)

  [vue-zhihu-daily](https://github.com/hilongjw/vue-zhihu-daily)

  [vue-mobile-qq](https://github.com/hilongjw/vue-mobile-qq)

  [vue-shopping](https://github.com/andylei18/vue-shopping)

### About the Author

Weibo: [Water杨涛](http://weibo.com/u/3503321141)

```
// TODO

####《Developing WeChat App Interface with Vue2》

Complete development of features such as account registration, adding friends, implementing chat functionality, etc.

```
