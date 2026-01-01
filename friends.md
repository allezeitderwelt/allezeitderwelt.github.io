---
layout: article
titles: friends
key: page-about
comments: true
---
欢迎留言和我交换博客链接 :)   

我喜欢的博客 <3 ：

- [− 273.15 ℃](https://blog.sommercamp.xyz/)
- [无竹斋](https://bamboobone9.com/)
- [列珂](https://write.c7.io/ilke/)
- [萌荷里安](https://write.c7.io/c1air2/)
- [邓布利多的冥想盆](https://pensieve.wangxindi.org/)
- [馆长兜兜转转](https://writee.org/takethefall/)

我喜欢的论坛/空间 <3 ：
- [她乡 Women Overseas](https://forum.womenoverseas.com/)：智慧，包容，而慷慨的海外华人女性社群。
- [结绳志 Tying Knots](https://tyingknots.net/)：人类学的技艺，观点，与行动。
- [葡萄田 vallennox ](https://vallennox.com/)：感动了我很多年的很多故事。我会定期打钱的作者。
- [熱朱力新地](https://music.coms.asia/)：学习钢琴的建议和资源。
- [政治学的邀约](https://finelin.notion.site/8f0e84b281894a9fb599e5ac8c511faf)：有趣的政治学研究导读。
- [沈於淵](https://matters.town/@zscliterary)：特别喜欢Diasporic Letters合集。
- [小触手的书房](https://heiheihei.ca/): 水彩学习的课程和思考。感觉能学到很多东西！

---  

<head>
  <!-- ... -->
  <link
    rel="stylesheet"
    href="https://unpkg.com/@waline/client@v3/dist/waline.css"
  />
</head>
<body>
  <!-- ... -->
  <div id="waline"></div>
  <script type="module">
    import { init } from 'https://unpkg.com/@waline/client@v3/dist/waline.js';

  init({
      el: '#waline',
      serverURL: 'https://walinetest-sage.vercel.app',
      lang: 'en',
      locale: { 
  nick: 'Nickname',
  mail: 'E-Mail (optional)',
  link: 'Website (optional)',
  placeholder: 'Tell me what you think :) To comment you do not need to sign into anything.',
  },
      emoji: ['https://unpkg.com/@waline/emojis@1.2.0/tw-emoji',],
    });

  </script>

    <style>
      :root {
        /* 主题色 */
        --waline-theme-color: #7a629d;
        }
    </style>
</body>
