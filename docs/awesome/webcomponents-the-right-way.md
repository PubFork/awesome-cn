<div class="github-widget" data-repo="mateusortiz/webcomponents-the-right-way"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Web Components the Right Way

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;精选的Web组件资源精选列表.

[Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components) —一套不同的技术，使您可以创建可重用的自定义元素（其功能与其他代码封装在一起），并在Web应用程序中使用它们.



&gt; Web Components通过爱创造了正确的方式 [Mateus Ortiz](https://twitter.com/mteusortiz) 并由 [Serhii Kulykov](https://twitter.com/serhiikulykov)

## Introduction

- [The Holy Grail Of Reusable Components: Custom Elements, Shadow DOM, And NPM](https://www.smashingmagazine.com/2018/07/reusable-components-custom-elements-shadow-dom-npm/)
- [The Power of Web Components](https://hacks.mozilla.org/2018/11/the-power-of-web-components/)
- [Web components: the secret ingredient helping power the web](https://web.dev/web-components-io-2019/)

## Standards

### Custom Elements

自定义元素为作者提供了一种构建自己的功能齐全的DOM元素的方法.

- [HTML Living Standard: Custom elements](https://html.spec.whatwg.org/multipage/custom-elements.html)
- [A Guide to Custom Elements for React Developers](https://css-tricks.com/a-guide-to-custom-elements-for-react-developers/)
- [All about HTML Custom Elements](https://github.com/shawnbot/custom-elements)
- [Custom Elements v1: Reusable Web Components](https://developers.google.com/web/fundamentals/web-components/customelements)
- [Using Custom Elements (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/custom-elements)

### Shadow DOM

Shadow DOM描述了一种将多个DOM树组合到一个层次结构中的方法，以及这些树如何在文档中彼此交互，从而实现DOM更好的组合的方法.

- [DOM Living Standard: Interface `ShadowRoot`](https://dom.spec.whatwg.org/#interface-shadowroot)
- [DOM Living Standard: Shadow tree](https://dom.spec.whatwg.org/#shadow-trees)
- [Open vs. Closed Shadow DOM](https://blog.revillweb.com/open-vs-closed-shadow-dom-9f3d7427d1af)
- [Shadow DOM in depth](https://github.com/praveenpuglia/shadow-dom-in-depth)
- [Shadow DOM v1: Self-Contained Web Components](https://developers.google.com/web/fundamentals/web-components/shadowdom)
- [The Rise of Shadow DOM](https://medium.com/front-end-hacking/the-rise-of-shadow-dom-84aa1f731e82)
- [Using Shadow DOM (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM)
- [What is the Shadow DOM?](https://bitsofco.de/what-is-the-shadow-dom/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/shadow-dom)

### HTML Templates

 ` <template>  `元素用于声明可通过脚本克隆并插入文档的HTML片段.

- [HTML Living Standard: The `template` element](https://html.spec.whatwg.org/multipage/scripting.html#the-template-element)
- [&lt;template&gt;: The Content Template element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template)
- [Using templates and slots (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_templates_and_slots)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/html/semantics/scripting-1/the-template-element)

### CSS Shadow Parts

CSS Shadow Parts允许开发人员在Shadow DOM中公开某些元素以用于样式设计.

- [W3C First Public Working Draft](https://www.w3.org/TR/css-shadow-parts-1/)
- [CSS Shadow Parts are coming!](https://dev.to/webpadawan/css-shadow-parts-are-coming-mi5)
- [`::part()` CSS pseudo element](https://developer.mozilla.org/en-US/docs/Web/CSS/::part)
- [`part` global attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/part)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/css/css-shadow-parts)

### Polyfills

### Custom Elements polyfills

- [@webcomponents/custom-elements](https://github.com/webcomponents/polyfills/tree/master/packages/custom-elements) -由Polymer团队提供的Custom Elements polyfill.
- [document-register-element](https://github.com/WebReflection/document-register-element) -Andrea Giammarchi提供的Custom Elements polyfill.

### Customized Built-in Elements polyfills

- [@corpuscule/custom-builtin-elements](https://github.com/corpusculejs/custom-builtin-elements) -定制的内置元素polyfill由 [CorpusculeJS](https://github.com/corpusculejs).
- [@ungap/custom-elements-builtin](https://github.com/ungap/custom-elements-builtin) -定制的内置元素polyfill由 [ungap project](https://ungap.github.io).

### Shadow DOM shims

- [@webcomponents/shadydom](https://github.com/webcomponents/polyfills/tree/master/packages/shadydom) -ShadowDOM v1匀场.
- [@webcomponents/shadycss](https://github.com/webcomponents/polyfills/tree/master/packages/shadycss) -ShadowDOM样式封装垫片.
- [@lwc/synthetic-shadow](https://github.com/salesforce/lwc/blob/master/packages/@lwc/synthetic-shadow) -Shadow DOM polyfill by [LWC](https://lwc.dev).

### HTML Templates polyfills

- [@webcomponents/template](https://github.com/webcomponents/polyfills/tree/master/packages/template)  -最小的polyfill用于` <template>  `.
- [@ungap/import-node](https://github.com/ungap/import-node) -由IE11提供的`importNode` polyfill [ungap project](https://ungap.github.io).

## Articles

### Best Practices

- [Custom Element Best Practices](https://developers.google.com/web/fundamentals/web-components/best-practices)
- [Gold Standard Checklist for Web Components](https://github.com/webcomponents/gold-standard/wiki)
- [Guidelines for creating web platform compatible components](https://w3ctag.github.io/webcomponents-design-guidelines/)
- [Open Web Components Recommendations](https://open-wc.org)

### Styling

- [Styling a Web Component](https://css-tricks.com/styling-a-web-component/)
- [Thinking Through Styling Options for Web Components](https://css-tricks.com/thinking-through-styling-options-for-web-components/)
- [Styling in the Shadow DOM With CSS Shadow Parts](https://css-tricks.com/styling-in-the-shadow-dom-with-css-shadow-parts/)

### Interoperability

- [Custom Elements Everywhere](https://custom-elements-everywhere.com)
- [Custom Elements That Work Anywhere](https://robdodson.me/interoperable-custom-elements/)
- [JavaScript frameworks, meet Web Components](https://www.voorhoede.nl/nl/blog/javascript-frameworks-meet-web-components/)
- [Web Components: Seamlessly interoperable](https://medium.com/@sergicontre/web-components-seamlessly-interoperable-82efd6989ca4)

### Accessibility

- [Styling Accessibility: A Web Components Approach](https://medium.com/@cfscorreia/styling-accessibility-a-web-components-approach-dc2aa8123eb2)
- [The future of accessibility for custom elements](https://robdodson.me/the-future-of-accessibility-for-custom-elements/)
- [Web components still need to be accessible](https://www.24a11y.com/2018/web-components-still-need-to-be-accessible/)

### Use Cases

- [Frankenstein Migration: Framework-Agnostic Approach (Part 1)](https://www.smashingmagazine.com/2019/09/frankenstein-migration-framework-agnostic-approach-part-1/)
- [Frankenstein Migration: Framework-Agnostic Approach (Part 2)](https://www.smashingmagazine.com/2019/09/frankenstein-migration-framework-agnostic-approach-part-2/)
- [Reasons Web Components are perfect for a big company](https://medium.com/@sergicontre/reasons-web-components-are-perfect-for-a-big-company-28790d712ad5)
- [5 Reasons Web Components Are Perfect for Design Systems](https://ionicframework.com/blog/5-reasons-web-components-are-perfect-for-design-systems/)

### Case Studies

- [Bringing Order to Web Design Chaos (with Web Components)](https://dev.to/thatjoemoore/bringing-order-to-web-design-chaos--3fhb)
- [ING ❤ Web Components](https://dev.to/thepassle/ing--web-components-aef)
- [ING Open-Sources Lion, Its White-Label Web Component Library – Q&A with Thomas Allmer](https://www.infoq.com/articles/ing-open-sources-lion-web-component/)
- [Lessons Learned, making our app with Web Components](https://medium.com/samsung-internet-dev/lessons-learned-making-our-app-with-web-components-bf55379cfcda)
- [Making Web Components Work](https://engineering.mixpanel.com/2018/06/12/making-web-components-work/)
- [Shipping Web Components in 2020](https://dev.to/joe8bit/shipping-web-components-in-2020-2h54)
- [Web Components at Scale at Salesforce: Challenges Encountered, Lessons Learnt](https://www.infoq.com/news/2020/03/web-components-salesforce-lwc/)
- [web.dev engineering blog #1: How we build the site and use Web Components](https://web.dev/how-we-build-webdev-and-use-web-components/)
- [Why we use Web Components](https://viljamis.com/2019/why-we-use-web-components/) 由Viljami Salminen撰写.
- [Why we use Web Components](https://dev.to/ionic/why-we-use-web-components-2c1i) 由Max Lynch.

## Libraries

### Class Based

- [Corpuscule](https://github.com/corpusculejs/corpuscule) -基于装饰器的小型Web组件框架.
- [LitElement](https://lit-element.polymer-project.org)  -用于创建快速，轻量级Web组件的简单基类.  聚合物项目的一部分.
- [Lightning Web Components](https://github.com/salesforce/lwc) -快速的企业级Web组件基础.
- [Omi](https://github.com/Tencent/omi) -4kb JavaScript的下一代Web框架（Web组件+ JSX +代理+存储+路径更新）.
- [Polymer](https://polymer-library.polymer-project.org) -Polymer Project作者提供的原始Web组件库.
- [Skate](https://github.com/skatejs/skatejs) -Web组件库专注于功能渲染管线和较小的占用空间.
- [slim.js](https://github.com/slimjs/slim.js) -基于现代标准的快速，强大的前端微框架.
- [Stencil](https://github.com/ionic-team/stencil) -用于生成Web组件的编译器.

### Functional

- [atomico](https://github.com/atomicojs/atomico) -用于使用功能和挂钩基于Web组件创建界面的小型库.
- [fuco](https://github.com/wtnbass/fuco) -功能组件，如React，但用于Web组件.
- [haunted](https://github.com/matthewp/haunted) -针对Web组件实现的React的Hooks API.
- [hybrids](https://github.com/hybridsjs/hybrids) -用于使用简单实用的API创建Web组件的UI库.

### Other

- [preact-custom-element](https://github.com/bspaulding/preact-custom-element) -从preact组件生成/注册自定义元素.
- [remount](https://github.com/rstacruz/remount) -使用自定义元素将React组件安装到DOM.
- [@riotjs/custom-elements](https://github.com/riot/custom-elements) -使用Riot.js创建香草自定义元素的简单API.

## Component Libraries

- [Amber Components](https://github.com/bitrockteam/amber-components) -琥珀色设计系统的Web组件实现.
- [AMP HTML](https://github.com/ampproject/amphtml) -Web组件库，用于构建以可靠和快速的性能呈现的网页.
- [AXA Pattern Library](https://github.com/axa-ch/patterns-library) -使用Web组件构建的AXA CH UI组件库.
- [Brightspace UI core](https://github.com/BrightspaceUI/core) -收集用于构建Brightspace应用程序的Web组件.
- [Bronconents](https://github.com/marius2502/bronconents) -使用Lit-Element构建的现代Web组件.
- [Calcite Components](https://github.com/Esri/calcite-components) -用于Esri的Calcite设计框架的共享Web组件.
- [Carbon Custom Elements](https://github.com/carbon-design-system/carbon-custom-elements) -使用Web组件构建的Carbon设计系统的实验变体.
- [Chameleon Web Components](https://github.com/MaritzSTL/chameleon) -基于Chameleon设计系统收集与框架无关的元素.
- [Clever components](https://github.com/CleverCloud/clever-components) -由Clever Cloud制作的Web组件集合.
- [Elix](https://github.com/elix/elix) -用于常见用户界面模式的高质量，可定制的Web组件.
- [Helix UI](https://github.com/HelixDesignSystem/helix-ui) -Helix设计系统的Web组件库.
- [Lion Web Components](https://github.com/ing-bank/lion) -一套高性能，可访问且灵活的Web组件.
- [LRNWebComponents](https://github.com/elmsln/lrnwebcomponents/) -ELMS：LN为任何项目生产了Web组件.
- [Material Web Components](https://github.com/material-components/material-components-web-components) -材料设计实现为Web组件.
- [Microsoft Graph Toolkit](https://github.com/microsoftgraph/microsoft-graph-toolkit) -Microsoft Graph的Web组件集合.
- [Nuxeo Elements](https://github.com/nuxeo/nuxeo-elements) -用于使用Web组件通过Nuxeo构建Web应用程序的组件.
- [PatternFly Elements](https://github.com/patternfly/patternfly-elements) -灵活，轻量级的Web组件以及构建它们的工具的集合.
- [Pearson Web Components](https://github.com/pearson-ux/web-components) -Pearson的可共享组件库可帮助开发人员构建一致的UI.
- [Spectrum Web Components](https://github.com/adobe/spectrum-web-components) -使用Web组件构建的Adobe Spectrum设计语言实现.
- [Tradeshift Elements](https://github.com/Tradeshift/elements) -可重用的Tradeshift UI组件作为Web组件.
- [UI5 Web Components](https://github.com/SAP/ui5-webcomponents) -组件库在本地API的基础上提供了企业风味的糖.
- [Vaadin components](https://github.com/vaadin/vaadin) -用于构建业务Web应用程序的不断发展的高质量Web组件集.
- [Wired Elements](https://github.com/wiredjs/wired-elements) -手绘，粗略外观的一组通用UI元素.
- [Wokwi Elements](https://github.com/wokwi/wokwi-elements) -Arduino和各种电子零件的Web组件.

## Frameworks

### Angular

- [Angular Elements Overview](https://angular.io/guide/elements)
- [Building Custom Elements / Web Components with Angular 6](https://medium.com/@tomsu/building-web-components-with-angular-elements-746cd2a38d5b)
- [Using Web Components in Angular](https://coryrylan.com/blog/using-web-components-in-angular)
- [Web Components With Angular Ivy In 6 Steps](https://www.softwarearchitekt.at/post/2019/05/18/web-components-custom-elements-with-angular-ivy-in-6-steps.aspx)

### Vue

- [Create & Publish Web Components With Vue CLI 3](https://vuejsdevelopers.com/2018/05/21/vue-js-web-component/)
- [Get started with Vue web components](https://medium.com/@royprins/get-started-with-vue-web-components-593b3d5b3200)
- [Using Web Components in Vue](https://coryrylan.com/blog/using-web-components-in-vue)

## Tools

- [Cypress Daywalker](https://github.com/JaySunSyn/cypress-daywalker) -赛普拉斯的Web组件和Shadow DOM支持.
- [query-selector-shadow-dom](https://github.com/Georgegriff/query-selector-shadow-dom) -可以刺入Shadow DOM根的querySelector，对于自动测试很有用.
- [web-component-analyzer](https://github.com/runem/web-component-analyzer) -用于分析Web组件并发出文档/诊断信息的CLI.

## Books

- [Web Components in Action](https://www.manning.com/books/web-components-in-action) -本·法雷尔（Ben Farrell）的书，可在曼宁（Manning）早期发行计划中获得.
- [Web Component Essentials](https://leanpub.com/web-component-essentials) -书名：Cory Rylan，早期预览版可在Leanpub上获得.

## Tutorials

-“ **让我们构建Web组件！**” [Benny Powers](https://github.com/bennypowers)
  - [Part 1: The Standards](https://dev.to/bennypowers/lets-build-web-components-part-1-the-standards-3e85)
  - [Part 2: The Polyfills](https://dev.to/bennypowers/lets-build-web-components-part-2-the-polyfills-dkh)
  - [Part 3: Vanilla Components](https://dev.to/bennypowers/lets-build-web-components-part-3-vanilla-components-4on3)
  - [Part 4: Polymer Library](https://dev.to/bennypowers/lets-build-web-components-part-4-polymer-library-4dk2)
  - [Part 5: LitElement](https://dev.to/bennypowers/lets-build-web-components-part-5-litelement-906)
  - [Part 6: Gluon](https://dev.to/bennypowers/lets-build-web-components-part-6-gluon-27ll)
  - [Part 7: Hybrids](https://dev.to/bennypowers/lets-build-web-components-part-7-hybrids-187l)

-“ **网络组件：从零到英雄**” [Pascal Schilp](https://github.com/thepassle)
  - [Part 1: An introduction to writing raw Web Components](https://dev.to/thepassle/web-components-from-zero-to-hero-4n4m)
  - [Part 2: Supercharging Web Components with lit-html](https://dev.to/thepassle/web-components-from-zero-to-hero-part-two-38p4)
  - [Part 3: Web Components hero with LitElement](https://dev.to/thepassle/web-components-from-zero-to-hero-part-three-3c5h)

-“ **现代JavaScript教程**” [Ilya Kantor](https://github.com/iliakan)
  - [Part 1: From the orbital height](https://javascript.info/webcomponents-intro)
  - [Part 2: Custom Elements](https://javascript.info/custom-elements)
  - [Part 3: Shadow DOM](https://javascript.info/shadow-dom)
  - [Part 4: Template element](https://javascript.info/template-element)
  - [Part 5: Shadow DOM slots, composition](https://javascript.info/slots-composition)
  - [Part 6: Shadow DOM styling](https://javascript.info/shadow-dom-style)
  - [Part 7: Shadow DOM and events](https://javascript.info/shadow-dom-events)

-“ **如何：组件**” [Web Fundamentals](https://developers.google.com/web/fundamentals/)
  - [Overview](https://developers.google.com/web/fundamentals/web-components/examples)
  - [`<howto-checkbox>`](https://developers.google.com/web/fundamentals/web-components/examples/howto-checkbox)
  - [`<howto-tabs>`](https://developers.google.com/web/fundamentals/web-components/examples/howto-tabs)
  - [`<howto-tooltip>`](https://developers.google.com/web/fundamentals/web-components/examples/howto-tooltip)

-** CSS技巧**文章系列，作者： [Caleb Williams](https://css-tricks.com/author/calebdwilliams/)
  - [Part 1: An Introduction to Web Components](https://css-tricks.com/an-introduction-to-web-components/)
  - [Part 2: Crafting Reusable HTML Templates](https://css-tricks.com/crafting-reusable-html-templates/)
  - [Part 3: Creating a Custom Element from Scratch](https://css-tricks.com/creating-a-custom-element-from-scratch)
  - [Part 4: Encapsulating Style and Structure with Shadow DOM](https://css-tricks.com/encapsulating-style-and-structure-with-shadow-dom/)
  - [Part 5: Advanced Tooling for Web Components](https://css-tricks.com/advanced-tooling-for-web-components/)

-《 Angular Elements》文章系列，作者： [Manfred Steyer](https://www.angulararchitects.io/about/)
  - [Part I: A Dynamic Dashboard In Four Steps With Web Components](https://www.angulararchitects.io/aktuelles/angular-elements-part-i/)
  - [Part II: Lazy and External Web Components](https://www.angulararchitects.io/aktuelles/angular-elements-part-ii/)
  - [Part III: Angular Elements Without Zone.Js](https://www.angulararchitects.io/aktuelles/angular-elements-part-iii/)
  - [Part IV: Content Projection with Slots in Angular Elements (>=7)](https://www.angulararchitects.io/aktuelles/content-projection-with-slots-in-angular-elements-7/)
  - [Part V: Your Options for Building Angular Elements with the CLI](https://www.angulararchitects.io/aktuelles/your-options-for-building-angular-elements/)

## Podcasts

- [Frontend Happy Hour, episode 62: Web Components - shots of shadow DOM](https://frontendhappyhour.com/episodes/web-components-shots-of-shadow-dom/)
- [Real Talk JavaScript, episode 7: Custom Web Components with Rob Wormald](https://realtalkjavascript.simplecast.fm/eaf3db9e)

## Benchmarks

- [web-components-benchmark](https://vogloblinsky.github.io/web-components-benchmark/) -带有各种示例的基准Web组件技术.
- [web-components-todo](https://wc-todo.firebaseapp.com/) -出于不同基准目的，在不同的Web组件库中构建了相同的todo应用程序.

## Usage Metrics

- [Chrome Platform Status: `CustomElementRegistryDefine`](https://chromestatus.com/metrics/feature/timeline/popularity/1689)
- [Chrome Platform Status: `ElementAttachShadow`](https://chromestatus.com/metrics/feature/timeline/popularity/804)
- [Chrome Platform Status: `HTMLTemplateElement`](https://chromestatus.com/metrics/feature/timeline/popularity/2769)

## Proposals

### Form-associated Custom Elements

- [Form Participation API Explained](https://docs.google.com/document/d/1JO8puctCSpW-ZYGU8lF-h4FWRIDQNDVexzHoOQ2iQmY/edit?usp=sharing) -由Google Chrome小组提供的文档.
- [Form-associated custom elements](https://www.chromestatus.com/features/4708990554472448) -Chrome平台状态中的功能.
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/custom-elements/form-associated)

### Custom State Pseudo class

- [Blink: Intent to implement](https://groups.google.com/a/chromium.org/forum/#!topic/blink-dev/CApU9QIu3TM)
- [`ElementInternals`'s `states` property and the `:state()` pseudo class](https://github.com/w3c/webcomponents/blob/gh-pages/proposals/custom-states-and-state-pseudo-class.md)

### Constructable Stylesheet Objects

- [Specification Draft](https://wicg.github.io/construct-stylesheets/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/blob/master/css/cssom/CSSStyleSheet-constructable.html)
- [Explainer](https://github.com/WICG/construct-stylesheets/blob/gh-pages/explainer.md)
- [Constructable Stylesheets](https://www.chromestatus.com/feature/5394843094220800) -Chrome平台状态中的功能.

## Miscellaneous

- [bruck](https://github.com/Heydon/bruck) -使用Web组件和Houdini Paint API构建的原型系统.
- [Vaadin Directory](https://vaadin.com/directory) -发布，讨论和评估Web组件
- [webcomponents.dev](https://webcomponents.dev) -您的Web组件工作室.
- [webcomponents.org](http://webcomponents.org/) -讨论和共享Web组件.
- [web-components-examples](https://github.com/mdn/web-components-examples) -与MDN Web组件文档相关的一系列Web组件示例.

## History

下面的文章描述了Web组件规范在标准化方面的悠久历史.
其中一些参考了早期的所谓的“ v0” Shadow DOM和“自定义元素”规范，而放弃了“ HTML导入”规范.
这些材料仅出于历史原因在这里，它们按年份分组并按时间顺序列出.

### 2019

- [Web Components in 2019: An Overview of the Most Exciting Proposals for the Web Platform Related to Web Components](https://scotch.io/bar-talk/an-overview-of-the-most-exciting-proposals-for-the-web-platform-related-to-web-components)

### 2018

- [Web Components 101: An Introduction to Web Components](https://www.telerik.com/blogs/web-components-101-an-introduction-to-web-components)
- [Web Components in 2018](https://www.sitepen.com/blog/2018/07/06/web-components-in-2018/)
- [Web Components Introduction: Creating Custom HTML Elements in 2018](https://www.grapecity.com/en/blogs/web-components-introduction-creating-custom-html-elements-2018)

### 2017

- [Web Components: The Long Game](https://infrequently.org/2017/10/web-components-the-long-game/)
- [The broken promise of Web Components](https://dmitriid.com/blog/2017/03/the-broken-promise-of-web-components/)
- [Regarding the broken promise of Web Components](http://robdodson.me/regarding-the-broken-promise-of-web-components/)

### 2016

- [Introducing Custom Elements](https://webkit.org/blog/7027/introducing-custom-elements/)
- [The Case for Custom Elements: Part 1](https://medium.com/dev-channel/the-case-for-custom-elements-part-1-65d807b4b439)
- [The Case for Custom Elements: Part 2](https://medium.com/dev-channel/the-case-for-custom-elements-part-2-2efe42ce9133)
- [Demythstifying Web Components](http://www.backalleycoder.com/2016/08/26/demythstifying-web-components/)
- [What's New in Shadow DOM v1 (by examples)](http://hayato.io/2016/shadowdomv1/)
- [Understanding Web Components](https://medium.com/the-ui-files/understanding-web-components-d051baa66019)

### 2015

- [Introducing Slot-Based Shadow DOM API](https://webkit.org/blog/4096/introducing-shadow-dom-api/)
- [Web Components and their role in the future of web development](http://kaytcat.github.io/web-components/)
- [Microsoft Edge and Web Components](https://blogs.windows.com/msedgedev/2015/07/15/microsoft-edge-and-web-components/)
- [Bringing componentization to the web: An overview of Web Components](https://blogs.windows.com/msedgedev/2015/07/14/bringing-componentization-to-the-web-an-overview-of-web-components/)
- [The state of Web Components](https://hacks.mozilla.org/2015/06/the-state-of-web-components/)

### 2014

- [A No-Nonsense Guide to Web Components](http://cbateman.com/blog/a-no-nonsense-guide-to-web-components-part-1-the-specs/)
- [Mozilla and Web Components: Update](https://hacks.mozilla.org/2014/12/mozilla-and-web-components/)
- [The State of the Componentised Web](https://www.leggetter.co.uk/2014/08/06/state-componentised-web.html)
- [Web Components and you – dangers to avoid](https://christianheilmann.com/2014/04/18/web-components-and-you-dangers-to-avoid/)
- [The Web's Declarative, Composable Future](https://addyosmani.com/blog/the-webs-declarative-composable-future/)
- [The Shadow DOM Diaries](https://gist.github.com/dglazkov/efd2deec54f65aa86f2e)
- [A Detailed Introduction To Custom Elements](https://www.smashingmagazine.com/2014/03/introduction-to-custom-elements/)

### 2013

- [A Guide to Web Components](https://css-tricks.com/modular-future-web-components/)
- [HTML's New Template Tag](https://www.html5rocks.com/en/tutorials/webcomponents/template/)

### 2012

- [Notes on Web Components + ARIA](https://developer.paciellogroup.com/blog/2012/07/notes-on-web-components-aria/)
- [Introduction to Web Components](https://www.w3.org/TR/2012/WD-components-intro-20120522/)

### 2011

- [Web Components and Model Driven Views by Alex Russell](https://fronteers.nl/congres/2011/sessions/web-components-and-model-driven-views-alex-russell)
- [What the Heck is Shadow DOM?](https://glazkov.com/2011/01/14/what-the-heck-is-shadow-dom/)

## Who To Follow

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://twitter.com/polymer">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1063502058337136640/RmlG_bbW_80x80.jpg">
          <div>聚合物</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/stenciljs">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1135534552137510914/5ZzvOFFp_80x80.png">
          <div>模版</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/openwc">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1101188623930662912/YKlBD7n6_80x80.png">
          <div>open-wc.org</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/webcomp_dev">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1169270943371407360/U-90Bxn0_80x80.jpg">
          <div>webcomponents.dev</div>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://twitter.com/justinfagnani">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/378800000808710206/2dbdaa1cb7b0db02f997aea5b40f29b8_80x80.jpeg">
          <div>贾斯汀·法格纳尼（Justin Fagnani） </div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/viljamis">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/671595827740086273/wCUWq-1S_80x80.png">
          <div>Viljami Salminen</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/JanMiksovsky">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/675000078055051264/u1ZEQfeE_80x80.jpg">
          <div>扬·米科索夫斯基</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/serhiikulykov">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1028197887329685504/cM6nOHlp_80x80.jpg">
          <div>谢里·库里科夫（Serhii Kulykov） </div>
        </a>
      </td>
    </tr>
  <tbody>
</table>

## License

版权所有2014-2018，保留所有权利.

根据以下方式许可的代码：
[MIT license](http://mateusortiz.mit-license.org)

@作者Mateus Ortiz <mteusortiz@gmail.com>
