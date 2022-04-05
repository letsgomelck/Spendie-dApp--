# 毕业设计 Spendie dApp

## 1. 代码仓库

### 1.1 gitlab repo

https://gitlab.com/spendie



### 1.2 客户要求代码规范

https://spendie.atlassian.net/wiki/spaces/DEV/pages/425985/Coding+Style+Guidelines?redirectCount=1



Code Styling Guide https://spendie.atlassian.net/l/c/2cxC5q1U



Annouk写的设计规范（总的设计大纲）Spendie Design brief: https://spendie.atlassian.net/wiki/spaces/DEV/pages/262152/Spendie+Design+brief

![Screen Shot 2022-03-23 at 22.45.43](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-23 at 22.45.433WCgRI.png)

### 1.3 设计的UI/UX

[**https://spendie.invisionapp.com/homepage**](https://spendie.invisionapp.com/homepage)



### 1.4 Jira （Sprint在里面，Agile）

https://spendie.atlassian.net/jira/software/c/projects/SP/boards/1/backlog?view=detail&selectedIssue=SP-7&issueLimit=100&atlOrigin=eyJpIjoiODBmZWJiNjFlY2NjNDFiOWI3NzFiNWYxYjI2M2I0MzciLCJwIjoiamlyYS1zbGFjay1pbnQifQ





Backlog https://spendie.atlassian.net/jira/software/projects/SRP/boards/3/backlog

### 1.5 Confluence

（上面也有提到）Annouk写的设计规范（总的设计大纲）Spendie Design brief: https://spendie.atlassian.net/wiki/spaces/DEV/pages/262152/Spendie+Design+brief







![Spendie S logo - White-02.png](https://static.wixstatic.com/media/2c7e93_259902dd7fb847ac8db491737071e03b~mv2.png/v1/fill/w_178,h_60,al_c,usm_0.66_1.00_0.01,enc_auto/Spendie S logo - White-02.png)



## 2. Governance repo

https://gitlab.com/hyprojects/withtally/

他们的产品是和withTally（一个链上治理社区 on-chain governance）（用HardHat部署复合式治理的代码）



<u>*所以这个project被governance的应该是withTally*</u>？？？（week 4的客户会议我回答的时候有提到）



withTally是一个**分布式自治组织（****The DAO****）****http://www.woshipm.com/blockchain/952552.html**







## 3. 有趣的链接

### 3.1 核心 Core stuff

1）ETH以太坊 Ethereum是以太坊技术，ether（ETH）是以太币 https://ethereum.org/en/

2）Matic/Polygon ( the layer 2 blockchain the smart contracts will be deployed to第二层区块链的智能合约将被部署到）https://polygon.technology/



We are using the Polygon network for our stable token as it is a low cost layer 2 solution. Therefore, we build smart contracts in Solidity. we use Hardhat for our development platform. it manages the ABIs and unit testing, etc. The frontend (what we have, so far) is built in Vue.js. You can see the projects on github https://gitlab.com/spendie/.

![Screen Shot 2022-03-23 at 21.59.38](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-23 at 21.59.38hu91gs.png)



3）Solidity（language for smart contracts智能合约所用语言）https://solidity.readthedocs.io/

4）Vue（前端平台）http://vuejs.org/

5）Vuetify（vue的style样式，使用方便）https://vuetifyjs.com/en/

6）Matamask（开发要用到，ETH、Polygon等的网页版加密货币钱包）https://metamask.io/



### 3.2 需要用到的自由软件Libs we are using

1）OpenZeppelin governance (tokenized governance,很有趣）https://docs.openzeppelin.com/contracts/4.x/api/governance

2）OpenZeppelin contracts（以熟悉的方式调用智能合约making calls to smart contracts in a familiar way）https://github.com/OpenZeppelin/openzeppelin-contracts/

3）Uniswap API docs(加密货币交换平台)https://uniswap.org/docs/v2/



### 3.3 这些知道就最好了，对区块链的必备知识

1）IPFS（p2p存储，部署网站/文件存储）https://ipfs.io/

2）OrbitDB（无耻的插件，但是很好对p2p数据库）https://github.com/orbitdb/orbit-db

3）Hardhat（智能合约开发平台）https://hardhat.org/

4）Waffle（智能合约测试）https://getwaffle.io/

5）ChaiJS（TDD单元测试的断言库）https://www.chaijs.com/

6）Linting and prettifying（找出代码错误，保证代码质量，美化工具）https://www.freecodecamp.org/news/dont-just-lint-your-code-fix-it-with-prettier/



### 3.4 一般事项 General stuff

什么是stable coin（这个项目的全部意义，the whole point of this project，例如有USDC，Dai，Pax）https://www.coinbase.com/learn/crypto-basics/what-is-a-stablecoin



## 4. 项目管理工具Scrum

**Jira**，为了Agile敏捷开发（链接在👆）





## 5. Sprint 1 - Sprint 6

### 5.1 Sprint 1，**2022-0314-0328**

基础页面basic page

按钮布局结构menu structure

Configure development environments.

设计Complete design

Get the page structure and menu in place, as well as moving the dApp to the Test Harness and creating a production environment dApp.

 

#### SRP-2 （Sam/Tae）（user）用tokens兑换spAUD，https://quickswap.exchange/#/swap

#### SRP-9（Hayden大佬） [admin]可以把dApp移植到dAPP测试线束（test harness自动化测试框架）

#### SRP-10（Hayden大佬） [admin]搭建开发环境

#### SRP-11（Sara，Tony） （user）开发连贯coherent look的外观给我们的dApp网页

#### SRP-12（Ann）[admin]用InVision的页面设计



### 5.2 Sprint 2，**0328-0411**

连接issuance和redeem页面，发行和赎回页面



### 5.3 **Sprint3 0411-0425,**

搭建swap和pool页面，互换和资金池





### 5.4 **Sprint4 0425-0509,**

打磨前面3个sprint的内容，测试和找出错误messages



### 5.5 **Sprint5 0509-0523,**

Wire up贷款页面搭建



### 5.6 **Sprint6 0523-0606，**

打磨贷款页面





## 6. 小组联系方式

### 6.1 Mentor

毕业课题mentor, 

[mohitkhosla70@gmail.com](mailto:mohitkhosla70@gmail.com)

mohit.khosla@rmit.edu.au



### 6.2 客户 Client

每周一下午4点（北京时间1点）客户会议

Anouk Pinchetti

[anouk@spendie.io](mailto:anouk@spendie.io)

Phone：0484005661



Hayden，合伙人，也是lead developer，可以询问unit testing，结对编程



### 6.3 4人小组

每周4上午11点（北京时间8点），半小时以上的小组会议



Canvas是 Project Group 18



1个 UI/UX 设计师(Ann)

1个 小领导(Tony)

3个 前端开发，最好优先React(Sam,Sara,Tony)



我们都需要学vue.js

**Sara, s3808578@student.rmit.edu.au**

**Tae/Sam, s3771369@student.rmit.edu.au**

**Ann, s3791827@student.rmit.edu.au**

**Tony, s3737937@student.rmit.edu.au**





**s3808578@student.rmit.edu.au**

**s3771369@student.rmit.edu.au**

**s3791827@student.rmit.edu.au**



**s3737937@student.rmit.edu.au**



小组时间表 

Sara Imamura，周二下午3点和周五下午不行



Tae Hyun Jin，都行 ([s3771369@student.rmit.edu.au](mailto:s3771369@student.rmit.edu.au))，懂solidity，有hardhat，react，ipfs和openzeppelin的开发经验。



Anushee Haque，会用Invision，周四周五不行([s3791827@student.rmit.edu.au](mailto:s3791827@student.rmit.edu.au))



### 6.4 交流工具

Slack

Zoom



### 6.5 Course Coordinator

Dr Vic Ciesielski，

[titan.csit.rmit.edu.au/~e23005](http://titan.csit.rmit.edu.au/~e23005)

[ (Links to an external site.)](http://titan.csit.rmit.edu.au/~e23005)





## 7. Web 3.0

(Vue.js) ，npm有一些插件eslint，prettier，npmjs.com



##  8. 选课题时附件

**毕业课题：Spendie** **（46）https://app.smartsheet.com/b/publish?EQBCT=4afa654d359549d5aff3320ce6db0a2a**

去中心化app UI设计，也有开发团队帮忙（类似实习）.

项目名称：Stablecoin dApp front end

目标：a sleek , sophisticated and user-friendly front-end

> 一个时尚、精致和用户友好的前端。



自身官网是由Wix打造 www.spendie.io



课题附件打开方式：https://draw.io



## 9. 前端要求

### 9.1 Vue.js v2

用v2不用v3因为v3有问题



如果React.js转过来可以看，https://dev.to/vincentntang/learning-vue-as-a-react-developer-385l



![Screen Shot 2022-03-23 at 22.43.50](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-23 at 22.43.50M1hh2C.png)





### 9.3 Vue代码规范 from Hayden

![Screen Shot 2022-03-23 at 23.01.10](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-23 at 23.01.10JjmSqt.png)



#### 9.3.1 This coding standard extends the official [Vue.js best practices](https://v2.vuejs.org/v2/style-guide/) and should be referred to when developing Vue-specific code.

多参考https://v2.vuejs.org/v2/style-guide/



#### 9.3.2  命名规则 

**Vue files** should be stored under components and views.

**Vue files** SHOULD be named using the PascalCase style, E.g.

```
ControlPanel.vue
```

**Vue components** SHOULD use the [MultiWord file naming convention](https://eslint.vuejs.org/rules/multi-word-component-names.html) to avoid clashes with future HTML elements, e.g. MyStuff.vue rather than Stuff.vue.

Group **Vue components** when it makes sense to do so. For example, AddLiquidityPanel.vue, RemoveLiquidityPanel.vue, LiquidityStatus.vue could be grouped under a directory called “swap”.

**Vue components** should not be too deeply nested. Use multiword names to describe the file:

**GOOD**

```
ThisIsMightyTighty.vue
/modals/LookinGood.vue
```

**BAD**

```
you/gotta/be/kidding/me/this/is/a/JokeRight.vue
```



#### 9.3.3 File Formatting

 **Vue-based Projects**

The following formatting standards MUST be applied to all text-based source files:

- 2 space indent
- 80 character max width
- Bracket spacing, E.g. `{ "some text" }`
- Double quotes around text, E.g. `import Something from "./path/to/somewhere";`
- Constants MUST be UPPERCASE, E.g. `AWSCONFIG`. Underscores are optional for longer constant names, E.g. `MY_REALLY_LONG_CONSTANT`.
- Javascript MUST be terminated with a semi-colon, E.g. `console.log("Hello World");`
- File imports MUST use the tilde “~” symbol when importing from the project’s root. E.g. `import Something from "~/some/node/module";`

In addition to the above File Formatting requirements, Javascript and Typescript files (including Vue) SHOULD use the [Semi Standard](https://github.com/standard/semistandard) coding style unless it contradicts the requirements outlined in [File Formatting](https://minertoken.atlassian.net/wiki/spaces/MT/pages/1500610565/Coding+Style+Guidelines#File-Formatting). If so, File Formatting should be the default coding style.



#### 9.3.4 Nuxt管理多页面

Nuxt introduces additional features for managing multi-page server side and static web sites. When working with Nuxt, the following coding rules should be followed:

**Nuxt Page and Layout files** MUST be named using kebab case, e.g.

```
/pages/about.vue
/pages/contact-us.vue
```

Sub-directories can be used to extend paths:

```
/pages/my-profile/dashboard.vue
/pages/my-profile/stats-dashboard.vue
```

although the second example would benefit from an extended directory structure called stats, I.e.

```
/pages/my-profile/stats/dashboard.vue
```

**Nuxt Pages** SHOULD provide a base page for any pages grouped by a directory, e.g.

```
/pages/my-profile.vue
/pages/my-profile/dashboard.vue
/pages/my-profile/dashboard/edit.vue
```

**Nuxt Layouts** SHOULD use a simple naming convention that describes the purpose of the layout, e.g.

```
default.vue
blog.vue
error.vue
my-profile.vue
```

Use a single word name (blog.vue) for the layout where possible.





## 10. Development Best Practice 开发最佳范例

![Screen Shot 2022-03-23 at 23.10.24](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-23 at 23.10.24VLHzPS.png)

### 10.1  前端还有测试还需要用到

 Frontend, UI/UX Development

- **Use Vue.js** for frontend development,
- **Include Nuxt.js** for sites which are more complex than a single page application (SPA),
- For unit testing we use **Mocha with Chai** assertions,
- For end-to-end (e2e) testing we use **Cypress**,
- **Use Typescript** instead of Javascript where possible. Configuration files, constants and utilities are good candidates for Typescript,



### 10.2  Typescript

> Typescript 代替 Javascript





### 10.3 Project Configuration

- Use Vue’s CLI tools to create a new Vue project (if not using Nuxt) `vue create my-project`[<img src="https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/favicongvdCx1.png" alt="img" style="zoom:25%;" />Creating a Project | Vue CLI](https://cli.vuejs.org/guide/creating-a-project.html) ,

- If using Nuxt, use Nuxt’s app creator, `npx create-nuxt-app <project-name>`. See [![img](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/icon_64x64.a3b4cejFqgvG.png)Installation](https://nuxtjs.org/docs/get-started/installation/) .



### 10.4 Project Structure

- Add a directory called **/utils** for supporting functions and libraries of functions (when using export const and export default). This is useful for both smart contract unit testing using Javascript and Typescript and for Vue/Nuxt sites,





## 11. Managing Smart Contract Deployment

### 11.1 Generating Types with Typechain

需要添加 typescript-types 到 tsconfig.json来安装Typechain

IDE也需要配置typescript





## 12. 本项目前端开发环境搭建_npm安装

> npm好像就是node.js的包（第三方模块）管理工具，就是可以复用别人的javascript代码（变成了npm包）方便下载>



1)nodejs下载LTS长期稳定版，企业级项目推荐安装

https://nodejs.org/en/

``` javascript
node -v //查询版本
```

2)然后npm自动安装了

3)根据hayden的readme在IDE中配置和运行项目





# 13. Sprint 2  Loan Page

 [screenshot-app.aave.com-2022.03.24-18_29_12.pdf](../../../Downloads/screenshot-app.aave.com-2022.03.24-18_29_12.pdf) 



![设计稿-loan-screenshot-app.aave.com-2022.03.24-18_29_12](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/设计稿-loan-screenshot-app.aave.com-2022.03.24-18_29_12lw6GLC.png)







![Screen Shot 2022-03-24 at 18.31.41](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 18.31.41u3YRHX.png)



# 14. Sprint 1 Trade/ Home Page

~~Ant Design Vue , 用了less开发语言，定义了一系列全局/组件的样式变量 https://www.antdv.com/docs/vue/customize-theme-cn/~~



## 14.1 架构设计

Header

List

   -item

Footer



![Screen Shot 2022-03-26 at 19.23.50](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-26 at 19.23.50rF8oSE.png)





Architecture of Dapp Trade Body

1. TradeHeader

​     -1.1 TextWrapper

​     -1.2 Settings

2. TradePage(grid)

​      - 2.1<div>trade-currency-input

​            --  2.1.1 CurrencyInputContainer

​                    --- 2.1.1.1     CurrencyInputPanel

​                    --- 2.1.1.2     NumericalInput

​                    --- 2.1.1.3     button_CurrencySelect

​                    --- 2.1.1.4    CurrencyInput_LabelRow (show the real-time exchange rate)

 

​     - 2.2 ArrowWrapper

​     

​     - 2.3 trade-currency-output

​           --2.3.1 CurrencyInputContainer

​                  --- 2.3.1.1   CurrencyInputPanel (can reuse 2.1.1.1)

​                  --- 2.3.1.2     NumericalInput

​                  --- 2.3.1.3     button_CurrencySelect

​                  --- 2.3.1.4    CurrencyInput_LabelRow (show the real-time exchange rate)



3. TradeDetailsDropdown

4. #### buttonConnectWallet



## 14.2 按照架构把结构搭建好

1）在pages => index.vue => import 1个父组件即可

子组件

import TradeHeader from "@/components/TradeHeader";

import TradePage from "@/components/TradePage";

import TradeDetailsDropdown from "@/components/TradeDetailsDropdown";

import TradeConnectWallet from "@/components/TradeConnectWallet";





然后注册components

![Screen Shot 2022-03-26 at 19.38.59](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-26 at 19.38.59RsosYa.png)



2）在父组件中引入和注册子组件



![Screen Shot 2022-03-26 at 19.45.50](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-26 at 19.45.50iagvkE.png)





3）



## 14.3 下载Hayden要求的项目所需插件

Vuetify，官方文档，在terminal里打开`vue ui`然后选好项目，然后安装插件`vuetify`

![Screen Shot 2022-03-27 at 13.59.52](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-27 at 13.59.52i7vlCT.png)





然后在App.vue里注册import和

``` html
// src/plugins/vuetify.js

import Vue from 'vue'
import Vuetify from 'vuetify'
import 'vuetify/dist/vuetify.min.css'

Vue.use(Vuetify)

const opts = {}

export default new Vuetify(opts)
```







## 14.4 Nuxt.js



## 14.5 Unit Testing



# 15.week5的client会议需要提问：

## 15.1 public里的index.html在哪？有没有移动端的理想视口

```html
<meta name="viewport" content="width=device-width,initial-scale=1.0">
```

3. 





# 16.项目技术栈

## 16.1 框架 Nuxt.js

## 16.2 编程语言 Vue.js

## 16.3 基本style插件 Vuetify

## 16.4 TDD Unit Testing（Jest）

## 16.5 DevOps



``` vue
<!-- 
  from Vuetify_UI components_Avatars_Misc_Advanced usage
  https://vuetifyjs.com/en/components/avatars/#tile
 -->
  <!-- <v-container fluid>
    <v-row justify="center">
      <v-expansion-panels popout>
        <v-expansion-panel
          v-for="(message, i) in messages"
          :key="i"
          hide-actions
        >
          <v-expansion-panel-header>
            <v-row align="center" class="spacer" no-gutters>
              <!-- 
                Insert a fa fa-info-circle icon here later
               -->
              <!-- <v-avatar size="36px">
                <img
                  v-if="message.avatar"
                  alt="Avatar"
                  src="https://avatars0.githubusercontent.com/u/9064066?v=4&s=460"
                />
                <v-icon
                  v-else
                  :color="message.color"
                  v-text="message.icon"
                ></v-icon>
              </v-avatar> -->

              <v-col class="hidden-xs-only" sm="5" md="3">
                <strong v-html="message.name"></strong>
                <span v-if="message.total" class="grey--text">
                  &nbsp;({{ message.total }})
                </span>
              </v-col>

              <v-col class="text-no-wrap" cols="5" sm="3">
                <v-chip
                  v-if="message.new"
                  :color="`${message.color} lighten-4`"
                  class="ml-0 mr-2 black--text"
                  label
                  small
                >
                  {{ message.new }} new
                </v-chip>
                <strong v-html="message.title"></strong>
              </v-col>
              -->

              <v-col
                v-if="message.excerpt"
                class="grey--text text-truncate hidden-sm-and-down"
              >
                &mdash;
                {{ message.excerpt }}
              </v-col>
            </v-row>
          </v-expansion-panel-header>

          <v-expansion-panel-content>
            <v-divider></v-divider>
            <v-card-text v-text="lorem"></v-card-text>
          </v-expansion-panel-content>
        </v-expansion-panel>
      </v-expansion-panels>
    </v-row>
  </v-container> -->


<script>
export default {
  name: "TradeDetailsDropdown",
  data: () => ({
    messages: [
      {
        // avatar: "https://avatars0.githubusercontent.com/u/9064066?v=4&s=460",
        name: "1 spAUD = 1.03 AUD($0.9998)",
        excerpt: "transaction fee $0.01",
      },
    ],
    
    // Should refactor to Tables

    lorem:
      "Maximum sold        5382 MATIC Price Impact         0.86% Liquidity Provider Fee       16.06 MATIC",
  }),
};
</script>

class="grey--text text-truncate hidden-sm-and-down"
```





# 17. 上传Gitlab前准备

账号上加载SSH，一般是terminal里用官方给的脚本代码创建SSH但是我们是看不到的，然后再用脚本代码，自动复制，最后粘贴到gitlab上。完成SSH

![Screen Shot 2022-03-27 at 21.44.20](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-27 at 21.44.20oBrlGm.png)





feat:Trade page function



## 17.1 从Github上项目同步到本地

https://blog.csdn.net/mch2869253130/article/details/101536287

``` javascript
git init
// 也就是同步网络和本地，可以看到不同的branch
git remote add origin git@gitlab.com:spendie/dapp.git
git clone git@gitlab.com:spendie/dapp.git
```



## 17.2 然后切换到开发branch

``` javascript
// 有时候会有问题，比如这个项目
git branch 
// 可以过滤上面的代码，直接
git checkout SRP-11
```



## 17.3 自己的代码写好commit到branch

``` javascript
git checkout SRP-11
git add .
// 这个有规范，参考（Coding Style Guidelines）https://spendie.atlassian.net/wiki/spaces/DEV/pages/edit-v2/425985
git commit -m "feat:Trade function"
git push / git push --all 
```

https://education.github.com/git-cheat-sheet-education.pdf



## 17.4 COPY备份一份到letsgomelck github

1）生成SSH。https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent![Screen Shot 2022-03-27 at 22.18.42](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-27 at 22.18.42nC0MHK.png)

```shell
ssh-keygen -t rsa -b 4096 -C "letsgomelck@gmail.com"
```



因为我的mac有很多ssh key 所以需要ls -al ~/.ssh ![Screen Shot 2022-03-27 at 22.23.59](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-27 at 22.23.59esqX3i.png)





找到我的文件名，是id_rsa.pub （https://docs.github.com/en/authentication/connecting-to-github-with-ssh/checking-for-existing-ssh-keys）

![Screen Shot 2022-03-27 at 22.24.44](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-27 at 22.24.44ztzGmK.png)





# 18.项目介绍

## 18.1 SpAUD是基于ERC-20 Token Standard的一种虚拟stable coin

https://ethereum.org/en/developers/docs/standards/tokens/erc-20/

没有自己的blockchain，是在ETH区块链下的polygon网络下的稳定币

针对澳元市场，创始人想要每个spAUD值大概1澳币（希望在98cents和1.02澳元之间波动），这样才可以从中谋利，希望98cents买入，1.02澳元卖出。项目2022年10月上线初期，可能会允许在1.05左右波动，为了让市场可以发展下去。

![Screen Shot 2022-03-28 at 13.36.33](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-28 at 13.36.33XQuOJs.png)



以下是anouk聊天记录



hayden学历

![Screen Shot 2022-03-28 at 13.15.29](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-28 at 13.15.296c1hd3.png)



# 19. 项目最新消息

## 19.1 管理数字input/output用 BigNumber.js, 不要用Ethers.js 或 Web3.js(因为他们不能处理十进制数decimals)





![Screen Shot 2022-03-28 at 15.22.51](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-28 at 15.22.51DzdBZw.png)



## 19.2 接下里的开发为了便于check进度

比如As a user I want to issue some Spendie stable tokens for Matic

可以理解为 UI功能为了cover ‘issuance’这个功能,每个开发小task尽量能在几小时内完成。

所以可以分解为

Component for input box and an action button

Component for interacting with Issuance

Component for interaction with the issuance smart contract

Component for calculating swap values

Component for hitting the submit button

![Screen Shot 2022-03-28 at 15.34.52](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-28 at 15.34.52bGdRaC.png)







```
ssh-keygen -t rsa -C "letsgomelck@gmail.com" -f /Users/cktonysw/.ssh/id_rsa_letsgomelck
```

![Screen Shot 2022-03-28 at 15.45.25](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-28 at 15.45.25qXBiKj.png)



然后 ssh-add ~/.ssh/id_rsa_letsgomelck

![Screen Shot 2022-03-28 at 15.46.29](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-28 at 15.46.29TV8G0m.png)



接着**通过ssh-add -l来确认结果**



![Screen Shot 2022-03-28 at 15.47.07](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-28 at 15.47.07YW3MQz.png)



4.

```
#default rmit github
Host github.com
  HostName github.com
  IdentityFile ~/.ssh/id_rsa

Host github_letsgomelck
  HostName github.com
  IdentityFile ~/.ssh/id_rsa_letsgomelck
```



![Screen Shot 2022-03-28 at 16.08.56](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-28 at 16.08.56VElLLj.png)

```shell
$ pbcopy < ~/.ssh/id_rsa_letsgomelck.pub
```



![Screen Shot 2022-03-28 at 16.17.23](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-28 at 16.17.23GgE58w.png)



git@letsgomelck.github.com:letsgomelck/Spendie.git





# 20.问题解答

## 20.1 如果push有问题，key exchange，直接

`git init`即可解决

或者关闭shadowrocket即可解决



https://www.cnblogs.com/cxl-/p/16030326.html



https://blog.csdn.net/codebattle/article/details/103176843



https://blog.csdn.net/solo_ws/article/details/52484388



## 20.2 需要pair programming回答

> 20220405

1)怎么分栏，就是style吧应该，更好看

2）connect按钮怎么更好看

3）input 只能十进制问题

4）



# 21. pull request

## 21.1 第一次220405

Changes I've made

- add `TradeBody` component which is the issue function in the trade page
- import `TradeBody` component into pages`Trade` to make Issue function work
- add `TradeHeader` component which is the header section of the issue function
- add `TradeBody` component which is the body section of the issue function
- add `TradeConnectWallet` component which is the connectWallet section of the issue function
- add `TradeDetailsDropdown` component which is the detailsDropDown section of the issue function
- add `IssueTokeninputPanel` component which is the spAUD input Panel sub component of the `TradeBody`component
- add `IssuespAUDinputPanel` component which is the spAUD input Panel sub component of the `TradeBody`component



Changes Sara made

- added responsive navigation bar
- added tabs for issue, swap and redeem section inside trade page
- added auto-redirect to trade page whenever home page is accessed
- changed to light theme styling

![Screen Shot 2022-04-05 at 21.59.33](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-04-05 at 21.59.33VGxugz.png)





![Screen Shot 2022-04-05 at 22.00.00](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-04-05 at 22.00.00Iicp5d.png)









![Screen Shot 2022-04-05 at 22.00.28](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-04-05 at 22.00.2822sO6i.png)

