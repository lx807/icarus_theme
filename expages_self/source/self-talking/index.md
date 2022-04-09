---
title: 闲言碎语
date: 2022-04-06 00:12:13
comments: false
thumbnail: https://cdn.jsdelivr.net/gh/lx807/blog_image@master/image/self_talking.png
---
<div class = "text-center"><h1>闲言碎语</h1></div><div class = "text-tips">


tips：github登录后按时间正序查看、可点赞加❤️、本插件[地址](https://github.com/removeif/gitalk)..<span id="busuanzi_container_page_pv">「<span id="busuanzi_value_page_pv">+99</span>次查看」</span></div>
<div id="comment-container1"><div class="text-tips">闲言碎语页面加载中，请稍等...</div></div>

<link rel="stylesheet" href="https://cdnjs.loli.net/ajax/libs/gitalk/1.6.0/gitalk.css"/>

<script>
    $.getScript("/js/gitalk_self.min.js", function () {
        var gitalk = new Gitalk({
            clientID: 'dc3155f604038230e85a',
            clientSecret: '199bbf073fd48557f790b751f6c684d4f6da943b',
            id: 'self_talk',
            repo: 'blog_issue',
            owner: 'lx807',
            admin: "lx807",
            createIssueManually: true,
            distractionFreeMode: false
        });
        gitalk.render('comment-container1');
    });
</script>