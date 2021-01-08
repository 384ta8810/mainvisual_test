<template>
  <div class="container">
    <header class="header">
      <div class="sidebar">
        <a href="">
          <img src="~/assets/images/logo_mark.svg" alt="" />
        </a>
        <ul>
          <li><a href="">Theme</a></li>
          <li><a href="">Work</a></li>
          <li><a href="">Video</a></li>
          <li><a href="">Teacher</a></li>
          <li><a href="">Map</a></li>
        </ul>
        <div class="link-students">
          <a href="">
            <img src="~/assets/images/icon_students_mono.svg" alt="" />
            <span>students</span>
          </a>
        </div>
      </div>
    </header>

    <main class="main">
      <section id="keyVisual" class="section-keyVisual">
        <div class="title">
          <h1 class="title-main">
            <img
              src="~/assets/images/title_main.svg"
              alt="卒業・進級制作展 日本電子専門学校 Webデザイン科"
            />
          </h1>
          <span class="title-sub">
            <img
              src="~/assets/images/title_sub.svg"
              alt="2021/2/10(水) 11(木) 12(金) 会場：日本電子専門学校7号館7階"
            />
          </span>
        </div>

        <div class="theme">
          <img
            v-prlx.mobile="{
              speed: 0.9,
              reverse: true,
            }"
            class="theme-image"
            src="~/assets/images/logo_type.svg"
            alt="Co-Growing+"
          />
        </div>

        <div class="layer">
          <div v-prlx="{ direction: 'x', speed: 0.8 }" class="layer-front">
            <div class="layer-front-content"></div>
            <div class="layer-front-shadow"></div>
          </div>

          <div class="layer-back">
            <div
              v-prlx.mobile="{
                speed: 0.4,
                reverse: true,
                direction: 'x',
              }"
              class="circle-01"
            >
              <div class="circle-01-in"></div>
            </div>
            <div
              v-prlx.mobile="{
                speed: 0.9,
                reverse: true,
                direction: 'x',
              }"
              class="circle-02"
            >
              <div class="circle-02-in"></div>
            </div>
          </div>
        </div>
      </section>

      <section id="welcome" class="section-welcome">
        <div class="welcome-content">
          <h2 class="heading-2 -welcome">
            <span>ようこそ</span>
            <span>日本電子専門学校<br />Webデザイン科</span>
            <span>卒業進級制作展 2020 へ</span>
          </h2>
        </div>
      </section>
    </main>
    <footer class="footer"></footer>
  </div>
</template>

<style lang="scss" scoped></style>

<script>
export default {
  //   mounted() {
  //     window.addEventListener('scroll', this.onScroll)
  //   },
  //   methods: {
  //     onScroll() {
  //       document
  //         .getElementById('test')
  //         .classList.toggle('original-translateX', window.scrollY > 0)
  //     },
  //   },
}
</script>
