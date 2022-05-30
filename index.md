投稿请注明：
  1.曲目名和作者
  2.曲目风格
  3.备注与联系方式
<link rel="stylesheet" href="https://unpkg.com/gitalk/dist/gitalk.css">
<script src="https://unpkg.com/gitalk/dist/gitalk.min.js"></script>
<div id="gitalk-container"></div>
var gitalk = new Gitalk({
    clientID: 'b3d5f212f43c29a2001b', // clientID 
    clientSecret: '28ad60c0a09adbe158debd0e3bcfc4c46d82ec32', // clientSecret
    repo: 'gitalk-comments', // 评论仓库名
    owner: 'progressive-tune',
    admin: ['Aislandz'], // 管理人
    id: location.pathname, // 返回当前 URL 的路径部分作为id
    language:'zh-CN', // 语言
    distractionFreeMode: false  // 无干扰模式
})
