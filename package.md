dependencies:

@casl/ability & @casl/react: 用于前端应用中的权限管理和访问控制。
@emotion/*: Emotion 是一个流行的 CSS-in-JS 库，用于在 React 组件中样式化。
@fullcalendar/*: FullCalendar 是一个高度可定制的日历视图库，用于显示日历事件。
@hookform/resolvers: 与 react-hook-form 配合使用，用于表单验证解析。
@iconify/react: 为 React 提供的图标集合库。
@mui/*: MUI (之前的名字是 Material-UI) 是一个流行的 React UI 框架，提供了许多预构建的组件和样式。
@popperjs/core & react-popper: 用于创建浮动和定位元素，例如 tooltips 和 popovers。
@reduxjs/toolkit & react-redux: Redux 是一个状态管理工具，这两个库是其核心及与 React 一起使用的工具。
apexcharts-clevision & react-apexcharts: ApexCharts 是一个现代图表库，与 React 配合使用。
axios & axios-mock-adapter: Axios 是用于 HTTP 请求的库，axios-mock-adapter 用于模拟 Axios 请求，主要在测试或开发中。
bootstrap-icons: 为 Bootstrap 提供的图标集。
chart.js & react-chartjs-2: Chart.js 是一个简单的图表库，react-chartjs-2 是它的 React 包装器。
cleave.js: 用于格式化输入的库，如电话号码或信用卡。
clipboard-copy: 一个用于复制文本到剪贴板的小库。
clsx: 一个轻量级的工具，用于在 React 中有条件地构建 className 字符串。
date-fns: 日期实用程序库。
draft-js: Facebook 提供的富文本编辑器框架。
i18next, i18next-browser-languagedetector & react-i18next: 国际化(i18n)和本地化(l10n)的解决方案。
jsonwebtoken: 用于处理 JSON Web Tokens 的库。
keen-slider: 一个用于创建滑动器的库。
next: Next.js 框架，用于 SSR、静态网站生成和路由。
nprogress: 一个进度条库。
payment: 用于处理和验证支付信息的库。
prismjs: 代码高亮库。
react & react-dom: React 库及其 DOM 绑定。
react-credit-cards: 用于创建信用卡输入的 UI 的库。
react-datepicker: 日期选择器组件。
react-dropzone: 为文件拖放交互创建区域的库。
react-hook-form: 用于表单验证和收集输入的库。
react-hot-toast: 一个轻量级的 toast 通知库。
react-perfect-scrollbar: 一个自定义滚动条库。
recharts: 一个基于 D3 的图表库，专门为 React 而构建。
stylis & stylis-plugin-rtl: 用于 CSS 解析和处理，特别是 RTL (从右到左) 文本。
yup: 一个 JavaScript 的对象验证库。

devDependencies:
这些大多是开发工具和类型声明文件，用于 TypeScript、ESLint (代码质量工具)、Prettier (代码格式化工具) 以及 @iconify 相关工具。

resolutions:
指定子依赖项的特定版本，这主要是为了确保特定的版本或解决依赖冲突。

overrides:
用于覆盖安装的包的特定字段。在这里，它似乎是在将 react-credit-cards 的某个依赖指向一个特定的别名。