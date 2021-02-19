内容来自于国外的《[30 seconds of code](https://www.30secondsofcode.org)》，只翻译了简单的描述，可对其做个整体了解，内容可用 Google 翻译，大体都能看懂。

与 [Underscore.js](https://underscorejs.org/) 和 [Lodash.js](https://lodash.com/docs/) 不同，30 seconds of code 中的代码片段都是各自独立的，可直接引用，也更容易吸收学习。

## JavaScript

## JavaScript Array Tricks

## JavaScript Algorithms

## CSS

## CSS Centering

## Node.js
1. [hashNode](https://www.30secondsofcode.org/js/s/hash-node)（使用SHA-256算法为值创建哈希并返回一个 Promise 对象）
2. [isDuplexStream](https://www.30secondsofcode.org/js/s/is-duplex-stream)（检查给定的参数是否为双工（可读和可写）流）
3. [isWritableStream](https://www.30secondsofcode.org/js/s/is-writable-stream)（检查给定的参数是否为可写流）
4. [isReadableStream](https://www.30secondsofcode.org/js/s/is-readable-stream)（检查给定参数是否为可读流）
5. [readFileLines](https://www.30secondsofcode.org/js/s/read-file-lines)（返回指定文件中的行数组）
6. [UUIDGeneratorNode](https://www.30secondsofcode.org/js/s/uuid-generator-node)（在NodeJS中生成一个UUID）
7. [isBrowser](https://www.30secondsofcode.org/js/s/is-browser)（确定当前运行时环境是否是浏览器，以便前端模块可以在服务器（节点）上运行而不会引发错误）
8. [JSONToFile](https://www.30secondsofcode.org/js/s/json-to-file)（将JSON对象写入文件）
9. [Tip: 使用Chrome开发人员工具调试 Node.js](https://www.30secondsofcode.org/blog/s/nodejs-chrome-debugging)
10. [colorize](https://www.30secondsofcode.org/js/s/colorize)（在文本中添加特殊字符以在控制台中以彩色打印（与console.log()组合））
11. [isNode](https://www.30secondsofcode.org/js/s/is-node)（确定当前运行时环境是否为Node.js）
12. [isStream](https://www.30secondsofcode.org/js/s/is-stream)（检查给定参数是否为流）
13. [hasFlags](https://www.30secondsofcode.org/js/s/has-flags)（检查当前进程的参数是否包含指定的标志）
14. [btoa](https://www.30secondsofcode.org/js/s/btoa)（从String对象创建一个base-64编码的ASCII字符串，其中字符串中的每个字符都被视为二进制数据的字节）
15. [untildify](https://www.30secondsofcode.org/js/s/untildify)（将波浪号路径转换为绝对路径）
16. [isTravisCI](https://www.30secondsofcode.org/js/s/is-travis-ci)（检查当前环境是否为Travis CI）
17. [atob](https://www.30secondsofcode.org/js/s/atob)（解码已使用base-64编码的数据字符串）
18. [requireUncached](https://www.30secondsofcode.org/js/s/require-uncached)（从缓存中删除模块后加载模块（如果存在））
19. [createDirIfNotExists](https://www.30secondsofcode.org/js/s/create-dir-if-not-exists)（创建目录（如果不存在））

## React Hooks
1. [usePersistedState](https://www.30secondsofcode.org/react/s/use-persisted-state)（返回持久存储在localStorage中的状态值，以及用于更新它的函数）
2. [useSSR](https://www.30secondsofcode.org/react/s/use-ssr)（检查代码是否在浏览器或服务器上运行）
3. [useAsync](https://www.30secondsofcode.org/react/s/use-async)（处理异步调用）
4. [useNavigatorOnLine](https://www.30secondsofcode.org/react/s/use-navigator-on-line)（检查客户端在线还是离线）
5. [useFetch](https://www.30secondsofcode.org/react/s/use-fetch)（以声明的方式实现 fetch）
6. [useUnload](https://www.30secondsofcode.org/react/s/use-unload)（处理beforeunload窗口事件）
7. [useDebounce](https://www.30secondsofcode.org/react/s/use-debounce)（Debounce 给定的值）
8. [useClickInside](https://www.30secondsofcode.org/react/s/use-click-inside)（处理在包装的组件内部单击的事件）
9. [useClickOutside](https://www.30secondsofcode.org/react/s/use-click-outside)（处理在包装的组件外部单击的事件）
10. [useMediaQuery](https://www.30secondsofcode.org/react/s/use-media-query)（检查当前环境是否匹配给定的媒体查询并返回适当的值）
11. [useCopyToClipboard](https://www.30secondsofcode.org/react/s/use-copy-to-clipboard)（将给定的文本复制到剪贴板）
12. [useTimeout](https://www.30secondsofcode.org/react/s/use-timeout)（以声明的方式实现 setTimeout）
13. [useComponentDidMount](https://www.30secondsofcode.org/react/s/use-component-did-mount)（挂载组件后立即执行回调）
14. [useComponentWillUnmount](https://www.30secondsofcode.org/react/s/use-component-will-unmount)（在卸载和销毁组件之前立即执行回调）
15. [useInterval](https://www.30secondsofcode.org/react/s/use-interval)（以声明的方式实现 setInterval）
16. [usePrevious](https://www.30secondsofcode.org/react/s/use-previous)（存储先前的 state 或 props）
17. [useToggler](https://www.30secondsofcode.org/react/s/use-toggler)（提供一个布尔状态变量，可以在其两个状态之间切换）

## React Components
1. [TagInput](https://www.30secondsofcode.org/react/s/tag-input)（标签输入字段）
2. [MultiselectCheckbox](https://www.30secondsofcode.org/react/s/multiselect-checkbox)（渲染一个复选框列表，该列表使用回调函数将其选定的一个或多个值传递给父组件）
3. [LimitedWordTextarea](https://www.30secondsofcode.org/react/s/limited-word-textarea)（具有字数限制的 textarea 组件）
4. [Modal](https://www.30secondsofcode.org/react/s/modal)（渲染可通过事件控制的 Modal 组件）
5. [Tabs](https://www.30secondsofcode.org/react/s/tabs)（选项卡式菜单和视图组件）
6. [Accordion](https://www.30secondsofcode.org/react/s/accordion)（具有多个可折叠内容元素的手风琴菜单）
7. [TreeView](https://www.30secondsofcode.org/react/s/tree-view)（可折叠内容的JSON对象或数组的树状图）
8. [RippleButton](https://www.30secondsofcode.org/react/s/ripple-button)（渲染一个按钮，当单击该按钮时可以对波纹效果进行动画处理）
9. [Alert](https://www.30secondsofcode.org/react/s/alert)（使用 prop 类型呈现警报组件）
10. [CountDown](https://www.30secondsofcode.org/react/s/count-down)（倒计时组件，该计时器在到达零时显示一条消息）
11. [FileDrop](https://www.30secondsofcode.org/react/s/file-drop)（文件拖放组件）
12. [StarRating](https://www.30secondsofcode.org/react/s/star-rating)（星级评分组件）
13. [MappedTable](https://www.30secondsofcode.org/react/s/mapped-table)（渲染具有从对象数组和属性名称列表动态创建的行的表）
14. [Tip: React 有条件的 className、空字符串和 null](https://www.30secondsofcode.org/blog/s/react-conditional-classname)
15. [Carousel](https://www.30secondsofcode.org/react/s/carousel)（轮播组件）
16. [如何在React中设置选择输入的值？](https://www.30secondsofcode.org/blog/s/react-selected-option)
17. [PropTypes.objectOf() VS PropTypes.shape()](https://www.30secondsofcode.org/blog/s/react-proptypes-objectof-vs-shape)
18. [Select](https://www.30secondsofcode.org/react/s/select)（一个不受控制的\<select>元素，该元素使用回调函数将其值传递给父组件）
19. [Toggle](https://www.30secondsofcode.org/react/s/toggle)（切换组件）
20. [LimitedTextarea](https://www.30secondsofcode.org/react/s/limited-textarea)（具有字符数限制的textarea组件）
21. [Loader](https://www.30secondsofcode.org/react/s/loader)（渲染旋转加载程序组件）
22. [Tooltip](https://www.30secondsofcode.org/react/s/tooltip)（工具提示组件）
23. [AutoLink](https://www.30secondsofcode.org/react/s/auto-link)（将字符串呈现为纯文本，并将URL转换为适当的链接元素）
24. [Collapse](https://www.30secondsofcode.org/react/s/collapse)（渲染具有可折叠内容的组件）
25. [DataList](https://www.30secondsofcode.org/react/s/data-list)（从数组中渲染元素列表）
26. [ControlledInput](https://www.30secondsofcode.org/react/s/controlled-input)（呈现一个受控的\<input>元素，该元素使用回调函数来通知其父组件有关值更新的信息）
27. [UncontrolledInput](https://www.30secondsofcode.org/react/s/uncontrolled-input)（呈现一个不受控制的\<input>元素，该元素使用回调函数来通知其父组件有关值更新的信息）
28. [Slider](https://www.30secondsofcode.org/react/s/slider)（渲染一个不受控制的范围输入元素，该元素使用回调函数将其值传递给父组件）
29. [DataTable](https://www.30secondsofcode.org/react/s/data-table)（可动态创建行的表格）
30. [PasswordRevealer](https://www.30secondsofcode.org/react/s/password-revealer)（使用显示按钮呈现密码输入字段）
31. [TextArea](https://www.30secondsofcode.org/react/s/text-area)（呈现一个不受控制的\<textarea>元素，该元素使用回调函数将其值传递给父组件）
32. [Mailto](https://www.30secondsofcode.org/react/s/mailto)（一个设置为发送电子邮件的链接（mailto：链接））
33. [Callto](https://www.30secondsofcode.org/react/s/callto)（呈现一个格式设置为呼叫电话号码的链接（电话：链接））

## React Rendering
1. [React 渲染基础](https://www.30secondsofcode.org/blog/s/react-rendering-basics)（深入了解React的渲染过程，并了解流行的JavaScript框架背后的基础知识）
2. [React 渲染优化](https://www.30secondsofcode.org/blog/s/react-rendering-optimization)（深入研究React的渲染过程，并了解如何进行小而强大的调整以优化性能）
3. [React 渲染状态](https://www.30secondsofcode.org/blog/s/react-rendering-state)（深入研究React的渲染过程并了解Context API和Redux在其中的作用）

## React Testing
1. [一种测试有状态 React 组件的方法](https://www.30secondsofcode.org/blog/s/testing-stateful-ui-components)
2. [测试使用React Testing库异步更新的 React 组件](https://www.30secondsofcode.org/blog/s/testing-async-react-components)
3. [使用React Testing Library测试Redux连接的组件](https://www.30secondsofcode.org/blog/s/testing-redux-connected-components)

