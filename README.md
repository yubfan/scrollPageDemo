# scrollPageDemo
这是一个滚动加载内容的小demo，最近项目中有滚动加载内容的需求，具体描述如下：
对于一次pipeline构建的构建日志来说，如果构建日志较长，内容较多，那么渲染到页面上的时间较久，用户体验较差
为了提升用户体验，后台加了分页，即每次请求返回200条日志，当用户查看完这200条日志，再次滚动滚动条，会再去后台查询200条

