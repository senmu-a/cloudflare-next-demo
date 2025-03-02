# 融合 CSR 和 SSR

## 保证服务端可以正常渲染 `senmu-vault` 项目

1. 构建部分 - nextjs 处理
2. http 服务部分 - nextjs 处理
3. 应用部分
  1.路由部分 - [x]改造适配 nextjs 的路由
  2.数据请求/预取部分 - [ ] TODO 需要改造
  3.中间件 - [ ]？？不清楚
  4.jsx -> html string - nextjs 处理
  5.TDK - [ ]？？不清楚
  6.CSS - tailwindCss，将原本的样式贴过来

## 保证可以部署到 cloudfare 和 aws Amplify

[ ] TODO
