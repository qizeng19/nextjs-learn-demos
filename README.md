# nextjs-learn-demos

NextJS项目demo汇总，每个demo开一个分支  

我的博客：[J实验室](https://weijunext.com)  
本仓库示例站：[nextjs.weijunext.com](https://nextjs.weijunext.com)  
开源SaaS产品仓库：[Smart Excel AI](https://github.com/weijunext/smart-excel-ai)  

<div align="center">
	<br>
	<a href="https://nextjs.weijunext.com">
		<img src="./public/website.svg" width="800" height="400" alt="Click to visit the demo website">
	</a>
	<br>
</div>

## 阅读代码请配合对应文章食用

### 本站技术栈  
|  分支   |  简介   | 文章链接  |
|  ----  |  ----   | ----  |
|        |  前置知识：NextJS v13 的渲染机制有什么不同？  | [👉 阅读文章](https://weijunext.com/article/31a22c65-66c5-4ebc-9bff-fe71a8300929) |
|      |  前置知识：NextJS v13服务端组件和客户端组件及最佳实践  | [👉 阅读文章](https://weijunext.com/article/9e02de2e-c76c-4b82-998a-9e7066450c42) |
|        |  拓展知识：讲清楚 Next.js 里的 CSR, SSR, SSG, 和 ISR  | [👉 阅读文章](https://weijunext.com/article/fa1588d6-c068-40ec-a587-4572bd349b25) |
| NextAuth-Prisma  | NextJS+Next-Auth+Postgres+Prisma来完成登录模块 | [👉 阅读文章](https://weijunext.com/article/061d8cd9-fcf3-4d9e-bd33-e257bc4f9989) |
| Docker | 探讨 Docker 和 Docker Compose 的使用 | [👉 阅读文章](https://weijunext.com/article/b33a5545-fd26-47a6-8641-3c7467fb3910) |
| Upstash | 用 Upstash 作为你的 Redis 服务器 | [👉 阅读文章](https://weijunext.com/article/6510121c-90da-4d20-85a1-72cbbdb3983b)  |
| contentlayer  | 让contentlayer帮你把md文件变成静态页面 | [👉 阅读文章](https://weijunext.com/article/49744a7c-f56b-43d7-8864-693ed3efa1a5) |
| membership  | 带你设计一套会员功能并开发它 | [👉 阅读文章](https://weijunext.com/article/ad3f4bff-0b78-4c04-bf12-98bffdc14611) |
| -  | 基于Lemon Squeezy开发你的全球可用的会员功能 | [👉 阅读文章](https://weijunext.com/article/integrate-lemonsqueezy-api) |
| metadata <br>sitemap  | Next.js的关键SEO配置 | [👉 阅读文章](https://weijunext.com/article/979b9033-188c-4d88-bfff-6cf74d28420d) |

### 增强用户体验功能 
|  分支   |  简介   | 文章链接  |
|  ----  |  ----   | ----  |
| AnimatedSvg  |  在SVG里写HTML和CSS，实现一个动画组件   | [👉 阅读文章](https://weijunext.com/article/animated-svg-component) |

### 精读 React Hooks
|  序号   |  Hook |  代码分支     | 文章链接  |
|  ----  | ----  |  ----   | ----  |
|  1 | useState | - | [👉 useState 的几个基础用法和进阶技巧](https://weijunext.com/article/36abddc1-a8cb-4618-b6eb-e536c4879535) |
|  2-3 | useReducer <br> useContext | useReducer-useContext | [👉 全面掌握useReducer](https://weijunext.com/article/486d38b7-bb0a-4493-a72c-01077000b098) <br> [👉 useContext从基础应用到性能优化](https://weijunext.com/article/99d401ae-7428-405d-8af5-5c23c582dec8) |
|  4 | useRef | useRef | [👉 useRef的多维用途](https://weijunext.com/article/f3460492-19ff-4214-8111-f1effa11e3ab) |
|  5 | useEffect | useEffect | [👉 useEffect使用细节知多少](https://weijunext.com/article/772e7900-ead5-4468-8a68-599e916bc651) |
|  6 | useLayoutEffect | useLayoutEffect | [👉 useLayoutEffect解决了什么问题](https://weijunext.com/article/fe61d9a6-84a1-4315-8e1d-34303cb2a497) |
|  7 | useMemo | useMemo | [👉 用useMemo来减少性能开销](https://weijunext.com/article/75704b53-4f6d-45db-a73b-f0cd6ce90ce9) |
|  8 | useCallback | - | [👉 我们为什么需要useCallback](https://weijunext.com/article/0db6ef00-d058-4204-8502-0990d06d0a4b) |
|  9 | useTransition | - | [👉 使用useTransition进行非阻塞渲染](https://weijunext.com/article/5458862c-76aa-436e-adc5-269dc82228df) |
|  10 | useDeferredValue | useDeferredValue | [👉 使用useDeferredValue延迟状态更新](https://weijunext.com/article/0ca90f65-4cc3-4a64-a6ab-de0b2fde87a3) |
|  11 | useInsertionEffect | - | [👉 useInsertionEffect——CSS-in-JS样式注入新方式](https://weijunext.com/article/ab3037b7-c0b6-4335-a869-431553a6b644) | 
|  12 | useImperativeHandle | useImperativeHandle | [👉 使用useImperativeHandle能获得什么能力](https://weijunext.com/article/9e8ce44c-238d-4eb7-b194-69493ac7c3e5) |
|  13、15 | useSyncExternalStore <br> useDebugValue| useSyncExternalStore | [👉 使用useSyncExternalStore获取实时数据](https://weijunext.com/article/7a4d45e4-ca6d-44ad-abfd-36ee9a5bb1a4) <br>  [👉 把useDebugValue加入你的React调试工具库](https://weijunext.com/article/01f63502-f459-4615-820d-a992d7322a89) |
|  14 | useId | - | [👉 总有一天你会需要useId为你生成唯一id](https://weijunext.com/article/ba0498cb-3bb5-4d76-a93f-ed7c51864fee) | 
|  16 | use | - | [👉 一个为代码优雅而生的hook——use](https://weijunext.com/article/4a9829b4-64ea-4254-bcf6-a9a2eb9cd131) |


## 关于我
前端工程师，全栈开发爱好者，AI降临派。  

[My Blog](https://weijunext.com)  
[Github](https://github.com/weijunext)  
[Twitter / X](https://twitter.com/weijunext)  
[Medium](https://medium.com/@weijunext)  
[掘金](https://juejin.cn/user/26044008768029)  
[知乎](https://www.zhihu.com/people/mo-mo-mo-89-12-11)  
[微信交流群](https://weijunext.com/make-a-friend)  


如果这个项目对你有用，请我喝杯咖啡吧

<a href="https://www.buymeacoffee.com/weijunextz" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;" ></a>