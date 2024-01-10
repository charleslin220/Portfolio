<template>
  <div class="homePage">
    <section class="hero" id="hero">
      <div class="hero-inner">
        <div class="info">
          <div class="title">
            <h1>Enter the Guild of In-Game Creators</h1>
          </div>
          <div class="content">
            <p>
              We empower players, developers and creators to make the best games
              even better through UGC
            </p>
          </div>
        </div>
        <div class="decoration" aria-hidden="true">
          <!-- <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="https://www.w3.org/2000/svg" class="loader">
                <path d="M19 10C19 14.9706 14.9706 19 10 19C5.02944 19 1 14.9706 1 10C1 5.02944 5.02944 1 10 1" stroke="white" stroke-width="2"/>
                </svg> -->
          <video
            class="hero-video-start"
            preload="none"
            poster="/pages/homepage/img/home/gate-closed.webp"
            data-static-poster="/pages/homepage/img/home/gate-open.jpg"
          >
            <!-- <source src="/pages/homepage/videos/home/home-hero-start.webm" type="video/webm"> -->
            <source
              data-src="/pages/homepage/videos/home/home-hero-start.mp4"
              type="video/mp4"
              src="/pages/homepage/videos/home/home-hero-start.mp4"
            />
          </video>
          <video
            class="hero-video-loop"
            preload="none"
            style="opacity: 1"
          >
            <!-- <source src="/pages/homepage/videos/home/home-hero-loop.webm" type="video/webm"> -->
            <source
              data-src="/pages/homepage/videos/home/home-hero-loop.mp4"
              type="video/mp4"
              src="/pages/homepage/videos/home/home-hero-loop.mp4"
            />
          </video>
        </div>
      </div>
      <div class="hero-footer">
        <section class="partners">
          <h3>Trusted by:</h3>
          <img
            src="/pages/homepage/img/home/partners/logitech.webp"
            alt="logitech"
          />
          <img src="/pages/homepage/img/home/partners/intel.webp" alt="intel" />
          <img src="/pages/homepage/img/home/partners/maxis.webp" alt="maxis" />
          <img src="/pages/homepage/img/home/partners/ea.webp" alt="ea" />
          <img src="/pages/homepage/img/home/partners/pubg.webp" alt="pubg" />
          <img
            src="/pages/homepage/img/home/partners/wild-card.webp"
            alt="wild card"
          />
          <img
            src="/pages/homepage/img/home/partners/ubisoft.webp"
            alt="ubisoft"
          />
          <img
            src="/pages/homepage/img/home/partners/twitch.webp"
            alt="twitch"
          />
          <img
            src="/pages/homepage/img/home/partners/mobalytics.webp"
            alt="mobalytics"
          />
          <img
            src="/pages/homepage/img/home/partners/mobile-logos.webp"
            width="375px"
            height="92px"
            class="mobile-logos"
            alt="all logos"
          />
          <div class="next-section">
            <a href="#cwu" title="scroll down">
              <svg>
                <use
                  href="/pages/homepage/img/home/logos.svg#arrowBigDown"
                ></use>
              </svg>
            </a>
          </div>
        </section>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts"></script>
