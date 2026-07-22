---
layout: splash
title: "러버덕 블로그에 오신 것을 환영합니다."
date: 2025-02-11
# toc: true
# toc_label: "목차"
# toc_icon: "list-squares"
# categories: about
# tags: [about]
# author_profile: true
permalink: /about/
# sidebar:
#   nav: "sidebar-category"
---

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  a,
  input {
    color: inherit;
    text-decoration: none;
  }
  a:hover,
  a:focus {
    text-decoration: none;
  }
  ul,
  ol {
    list-style: none;
  }

  .button_home{
    font-size: 14px;
    font-weight: bold;
    padding: 14px 24px;
    border: 2px solid rgb(255, 0, 132);
    border-radius: 999px;
    color: rgb(255, 0, 132);
    display: inline-flex;
    align-items: center;
    gap: 8px;
    opacity: 0;
    transition: 1s;
    transform: translateX(-100%);
  }
  @keyframes cloudy {
    0% {
      transform: translateY(-10px);
    }

    50% {
      transform: translateY(0px);
    }

    100% {
      transform: translateY(-10px);
    }
  }
  @keyframes blink {
    0% {
      opacity: 1;
    }
    100% {
      opacity: 0;
    }
  }

  .typing-text {
    min-height: 1.2em;
  }
</style>
<div
  style="
    position: relative;
    color: white;
    font-family:
      Noto Sans KR,
      sans-serif;
  "
>
  <div
    style="
      position: fixed;
      inset: 0;
      pointer-events: none;
      background:
        radial-gradient(circle at 18% 12%, rgba(255, 0, 183, 0.1), transparent 45%),
        radial-gradient(circle at 85% 75%, rgba(255, 46, 196, 0.07), transparent 40%);
      z-index: 0;
    "
  ></div>
  <div
    class="container"
    style="
      height: 800px;
      margin: 0 auto;
      padding: 20px 50px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      gap: 20px;
      position: relative;
    "
  >
    <div style="display: flex; align-items: center; gap: 20px">
      <img
        src="../assets/images/common/rubberDuck_logo.svg"
        alt="deok_logo"
        style="width: 70px; transform: rotateY(180deg); animation: cloudy 2s ease-in-out infinite"
      />
      <p style="font-size: 14px; color: #9aa0a6; margin-top: 2em">FRONTEND / FULLSTACK DEVELOPER</p>
    </div>
    <h1 style="font-size: 2.5rem; font-weight: 700; line-height: 1.2">
      <span class="typing-text" data-text="안녕하세요, 러버덕 블로그입니다."></span>
      <span style="animation: blink 1s infinite; color: rgb(255, 0, 132)">▍</span>
    </h1>
    <p style="font-size: 18px; line-height: 1.8; color: #9aa0a6; opacity:0; transition: 1s" class="sub_text">
      배운 것과 고민한 과정을 기록하며 스스로 돌아보고 — 필요할 때 다시 꺼내 보는 개발 블로그입니다.
    </p>
    <div>
      <a href="/" class="button_home">블로그 둘러보기 →</a>
    </div>
    <div style="position: absolute; bottom: 30px; color: #9aa0a6; font-size: 0.5rem">SCROLL ↓</div>
  </div>
  <section
    style="
      position: relative;
      z-index: 1;
      padding: 120px 50px;
      opacity: 1;
      transform: translateY(0px);
      transition:
        opacity 0.9s,
        transform 0.9s;
      border-top: 1px solid rgba(255, 255, 255, 0.06);
    "
  >
    <div
      style="
        font-family: &quot;JetBrains Mono&quot;, monospace;
        font-size: 12px;
        letter-spacing: 0.2em;
        color: rgb(255, 0, 132);
        margin-bottom: 18px;
      "
    >
      ABOUT
    </div>
    <h2
      style="
        font-size: clamp(24px, 3vw, 34px);
        font-weight: 600;
        line-height: 1.5;
        margin: 0px 0px 20px;
        max-width: 720px;
      "
    >
      안녕하세요,
      <span style="color: rgb(255, 0, 132)">박덕기</span>입니다.<br />다들 저를
      <span style="color: rgb(255, 0, 132)">러버덕</span>이라고 불러요.
    </h2>
    <p
      style="
        font-size: 16px;
        line-height: 1.85;
        color: rgb(154, 160, 166);
        max-width: 640px;
        margin: 0px;
      "
    >
      복잡한 문제를 소리 내어 설명하다 보면 실마리가 풀리곤 합니다. 이 블로그는 그 과정을 그대로
      옮겨 적은 기록이에요 — 막힌 부분, 삽질한 흔적, 찾아낸 답까지...<br />
      <i>누군가에게는 제가 그 옆에 놓인 작은 러버덕이 되었으면 합니다.</i>
    </p>
  </section>
  <section
    style="
      position: relative;
      z-index: 1;
      padding: 120px 50px;
      opacity: 1;
      transform: translateY(0px);
      transition:
        opacity 0.9s,
        transform 0.9s;
      border-top: 1px solid rgba(255, 255, 255, 0.06);
    "
  >
    <div
      style="
        font-family: &quot;JetBrains Mono&quot;, monospace;
        font-size: 12px;
        letter-spacing: 0.2em;
        color: rgb(255, 0, 132);
        margin-bottom: 18px;
      "
    >
      STACK
    </div>
    <div style="display: flex; flex-wrap: wrap; gap: 12px">
      <span
        style="
          font-size: 13px;
          padding: 10px 18px;
          border-radius: 8px;
          border: 1px solid rgba(255, 255, 255, 0.1);
          background: rgba(255, 255, 255, 0.02);
          color: rgb(211, 216, 220);
        "
        ><span class="sc-interp">HTML/CSS</span></span
      >
      <span
        style="
          font-size: 13px;
          padding: 10px 18px;
          border-radius: 8px;
          border: 1px solid rgba(255, 255, 255, 0.1);
          background: rgba(255, 255, 255, 0.02);
          color: rgb(211, 216, 220);
        "
        ><span class="sc-interp">JavaScript</span></span
      >
      <span
        style="
          font-size: 13px;
          padding: 10px 18px;
          border-radius: 8px;
          border: 1px solid rgba(255, 255, 255, 0.1);
          background: rgba(255, 255, 255, 0.02);
          color: rgb(211, 216, 220);
        "
        ><span class="sc-interp">TypeScript</span></span
      >
      <span
        style="
          font-size: 13px;
          padding: 10px 18px;
          border-radius: 8px;
          border: 1px solid rgba(255, 255, 255, 0.1);
          background: rgba(255, 255, 255, 0.02);
          color: rgb(211, 216, 220);
        "
        ><span class="sc-interp">React</span></span
      >
      <span
        style="
          font-size: 13px;
          padding: 10px 18px;
          border-radius: 8px;
          border: 1px solid rgba(255, 255, 255, 0.1);
          background: rgba(255, 255, 255, 0.02);
          color: rgb(211, 216, 220);
        "
        ><span class="sc-interp">Next.js</span></span
      >
      <span
        style="
          font-size: 13px;
          padding: 10px 18px;
          border-radius: 8px;
          border: 1px solid rgba(255, 255, 255, 0.1);
          background: rgba(255, 255, 255, 0.02);
          color: rgb(211, 216, 220);
        "
        ><span class="sc-interp">Node.js</span></span
      >
      <span
        style="
          font-size: 13px;
          padding: 10px 18px;
          border-radius: 8px;
          border: 1px solid rgba(255, 255, 255, 0.1);
          background: rgba(255, 255, 255, 0.02);
          color: rgb(211, 216, 220);
        "
        ><span class="sc-interp">Python</span></span
      >
      <span
        style="
          font-size: 13px;
          padding: 10px 18px;
          border-radius: 8px;
          border: 1px solid rgba(255, 255, 255, 0.1);
          background: rgba(255, 255, 255, 0.02);
          color: rgb(211, 216, 220);
        "
        ><span class="sc-interp">Infra/DevOps</span></span
      >
      <span
        style="
          font-size: 13px;
          padding: 10px 18px;
          border-radius: 8px;
          border: 1px solid rgba(255, 255, 255, 0.1);
          background: rgba(255, 255, 255, 0.02);
          color: rgb(211, 216, 220);
        "
        ><span class="sc-interp">Git</span></span
      >
    </div>
  </section>
  <section
    id="contact"
    style="
      position: relative;
      z-index: 1;
      padding: 120px 50px 140px;
      opacity: 1;
      transform: translateY(0px);
      transition:
        opacity 0.9s,
        transform 0.9s;
      border-top: 1px solid rgba(255, 255, 255, 0.06);
    "
  >
    <div
      style="font-size: 12px; letter-spacing: 0.2em; color: rgb(255, 0, 132); margin-bottom: 18px"
    >
      CONTACT
    </div>
    <div style="display: flex; flex-direction: column; gap: 14px; font-size: 17px">
      <a
        href="https://www.linkedin.com/in/%EB%8D%95%EA%B8%B0-%EB%B0%95-175621221/"
        target="_blank"
        style="color: rgb(238, 241, 243); display: flex; align-items: center; gap: 10px"
        >LinkedIn <span style="color: rgb(74, 81, 88); font-size: 13px">박덕기</span></a
      >
      <a
        href="https://github.com/Deokgi-Park"
        target="_blank"
        style="color: rgb(238, 241, 243); display: flex; align-items: center; gap: 10px"
        >GitHub <span style="color: rgb(74, 81, 88); font-size: 13px">@Deokgi-Park</span></a
      >
      <a
        href="mailto:ejrrl6931@gmail.com"
        target="_blank"
        style="color: rgb(238, 241, 243); display: flex; align-items: center; gap: 10px"
        >Email <span style="color: rgb(74, 81, 88); font-size: 13px">ejrrl6931@gmail.com</span></a
      >
    </div>
    <div
      style="
        margin-top: 64px;
        font-family: &quot;JetBrains Mono&quot;, monospace;
        font-size: 11px;
        color: rgb(74, 81, 88);
      "
    >
      Built with Jekyll · minimal-mistakes (neon)
    </div>
  </section>
  <script>
    document.addEventListener("DOMContentLoaded", function () {
      var typingElement = document.querySelector(".typing-text");
      var typingStartDelay = 1000;
      if (!typingElement) {
        return;
      }
      var fullText = typingElement.getAttribute("data-text") || "";
      var currentIndex = 0;
      function typeNextCharacter() {
        if (currentIndex > fullText.length) {
          document.querySelector(".sub_text").style.opacity = "1";
          window.setTimeout(()=>{
            document.querySelector(".button_home").style.opacity = "1";
            document.querySelector(".button_home").style.transform = "translateX(0)";
            },800)
          return;
        }
        typingElement.textContent = fullText.slice(0, currentIndex);
        currentIndex += 1;
        window.setTimeout(typeNextCharacter, 90);
      }
      window.setTimeout(typeNextCharacter, typingStartDelay);
    });

  </script>
</div>
