---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "\nJudehahh's Space"
  text: ""
  tagline: "新手上路\n\n"
  actions:
    - theme: brand
      text: 文档
      link: /00-before/about-me
    - theme: alt
      text: 博客
      link: /blog/index
  image:
    src: /avatar.jpeg

features:
  - title: 学习
    details: 记录学习
  - title: 工作
    details: 总结经验
  - title: 生活
    details: 分享生活
---

<style>
:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #bd34fe 30%, #41d1ff);

  --vp-home-hero-image-background-image: linear-gradient(-45deg, #bd34fe 50%, #47caff 50%);
  --vp-home-hero-image-filter: blur(44px);
}

@media (min-width: 640px) {
  :root {
    --vp-home-hero-image-filter: blur(56px);
  }
}

@media (min-width: 960px) {
  :root {
    --vp-home-hero-image-filter: blur(68px);
  }
}
</style>
