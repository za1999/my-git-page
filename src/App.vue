<template>
  <div class="page">
    <header class="topbar">
      <p class="brand">MY GIT PAGE</p>
      <a class="toplink" href="https://github.com" target="_blank" rel="noreferrer">
        GitHub
      </a>
    </header>

    <main class="hero">
      <p class="tag">Vue + Vite Starter, Rebuilt</p>
      <h1>把你的想法，放到一个真正能展示的首页里</h1>
      <p class="lead">
        这是一个干净、现代、可继续扩展的首页基础。你可以在这里继续接入项目介绍、作品卡片、联系方式或博客入口。
      </p>

      <div class="actions">
        <a class="btn btn-primary" href="#work">查看作品</a>
        <a class="btn btn-ghost" href="#about">了解我</a>
      </div>
    </main>

    <section id="work" class="grid">
      <article class="card">
        <p class="card-kicker">PROJECT 01</p>
        <h2>Landing Page</h2>
        <p>为个人品牌做的单页站，重点在视觉层次与动效节奏。</p>
      </article>

      <article class="card">
        <p class="card-kicker">PROJECT 02</p>
        <h2>Dashboard UI</h2>
        <p>信息密度高但不拥挤，移动端和桌面端都有一致体验。</p>
      </article>

      <article class="card">
        <p class="card-kicker">PROJECT 03</p>
        <h2>Content System</h2>
        <p>从排版、配色到组件粒度，建立稳定可复用的内容系统。</p>
      </article>
    </section>

    <section id="about" class="about">
      <h3>下一步你可以做什么</h3>
      <p>
        把按钮链接替换为真实页面，把卡片换成你的项目数据，再加上路由和接口，这个首页就能直接作为你的项目门户。
      </p>
    </section>
  </div>
</template>
