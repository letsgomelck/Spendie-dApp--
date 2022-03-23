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



Hayden，合伙人，也是lead programmer，可以询问unit testing，结对编程



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