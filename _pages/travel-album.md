---
title: "旅遊相簿"
layout: single
permalink: /travel-album/
header:
  overlay_color: "#000"
  overlay_filter: "0.2"
  overlay_image: /assets/images/travel/IMG_0908.HEIC
gallery:
  - url: /assets/images/travel/IMG_0074.HEIC
    image_path: /assets/images/travel/IMG_0074.HEIC
    alt: "旅遊照片 1"
    title: "旅遊照片 1"
  - url: /assets/images/travel/IMG_0104.HEIC
    image_path: /assets/images/travel/IMG_0104.HEIC
    alt: "旅遊照片 2"
    title: "旅遊照片 2"
  - url: /assets/images/travel/IMG_0286.HEIC
    image_path: /assets/images/travel/IMG_0286.HEIC
    alt: "旅遊照片 3"
    title: "旅遊照片 3"
  - url: /assets/images/travel/IMG_0554.HEIC
    image_path: /assets/images/travel/IMG_0554.HEIC
    alt: "旅遊照片 4"
    title: "旅遊照片 4"
  - url: /assets/images/travel/IMG_0908.HEIC
    image_path: /assets/images/travel/IMG_0908.HEIC
    alt: "旅遊照片 5"
    title: "旅遊照片 5"
  - url: /assets/images/travel/IMG_1150.HEIC
    image_path: /assets/images/travel/IMG_1150.HEIC
    alt: "旅遊照片 6"
    title: "旅遊照片 6"
  - url: /assets/images/travel/IMG_1159.HEIC
    image_path: /assets/images/travel/IMG_1159.HEIC
    alt: "旅遊照片 7"
    title: "旅遊照片 7"
  - url: /assets/images/travel/IMG_9261.HEIC
    image_path: /assets/images/travel/IMG_9261.HEIC
    alt: "旅遊照片 8"
    title: "旅遊照片 8"
  - url: /assets/images/travel/IMG_9350.HEIC
    image_path: /assets/images/travel/IMG_9350.HEIC
    alt: "旅遊照片 9"
    title: "旅遊照片 9"
  - url: /assets/images/travel/IMG_9749.HEIC
    image_path: /assets/images/travel/IMG_9749.HEIC
    alt: "旅遊照片 10"
    title: "旅遊照片 10"
  - url: /assets/images/travel/IMG_9917.HEIC
    image_path: /assets/images/travel/IMG_9917.HEIC
    alt: "旅遊照片 11"
    title: "旅遊照片 11"
---

從晨光到夜色，把路上的風景都收進這一頁。每一張照片都是一次出走的片刻，點開就是當時的溫度與心情。

{% assign travel_images = "/assets/images/travel" | relative_url %}
<figure class="album-grid">
  <button class="photo-button" type="button">
    <img class="heic-photo" src="{{ travel_images }}/IMG_0074.HEIC" data-heic="{{ travel_images }}/IMG_0074.HEIC" alt="旅遊照片 1" loading="lazy">
  </button>
  <button class="photo-button" type="button">
    <img class="heic-photo" src="{{ travel_images }}/IMG_0104.HEIC" data-heic="{{ travel_images }}/IMG_0104.HEIC" alt="旅遊照片 2" loading="lazy">
  </button>
  <button class="photo-button" type="button">
    <img class="heic-photo" src="{{ travel_images }}/IMG_0286.HEIC" data-heic="{{ travel_images }}/IMG_0286.HEIC" alt="旅遊照片 3" loading="lazy">
  </button>
  <button class="photo-button" type="button">
    <img class="heic-photo" src="{{ travel_images }}/IMG_0554.HEIC" data-heic="{{ travel_images }}/IMG_0554.HEIC" alt="旅遊照片 4" loading="lazy">
  </button>
  <button class="photo-button" type="button">
    <img class="heic-photo" src="{{ travel_images }}/IMG_0908.HEIC" data-heic="{{ travel_images }}/IMG_0908.HEIC" alt="旅遊照片 5" loading="lazy">
  </button>
  <button class="photo-button" type="button">
    <img class="heic-photo" src="{{ travel_images }}/IMG_1150.HEIC" data-heic="{{ travel_images }}/IMG_1150.HEIC" alt="旅遊照片 6" loading="lazy">
  </button>
  <button class="photo-button" type="button">
    <img class="heic-photo" src="{{ travel_images }}/IMG_1159.HEIC" data-heic="{{ travel_images }}/IMG_1159.HEIC" alt="旅遊照片 7" loading="lazy">
  </button>
  <button class="photo-button" type="button">
    <img class="heic-photo" src="{{ travel_images }}/IMG_9261.HEIC" data-heic="{{ travel_images }}/IMG_9261.HEIC" alt="旅遊照片 8" loading="lazy">
  </button>
  <button class="photo-button" type="button">
    <img class="heic-photo" src="{{ travel_images }}/IMG_9350.HEIC" data-heic="{{ travel_images }}/IMG_9350.HEIC" alt="旅遊照片 9" loading="lazy">
  </button>
  <button class="photo-button" type="button">
    <img class="heic-photo" src="{{ travel_images }}/IMG_9749.HEIC" data-heic="{{ travel_images }}/IMG_9749.HEIC" alt="旅遊照片 10" loading="lazy">
  </button>
  <button class="photo-button" type="button">
    <img class="heic-photo" src="{{ travel_images }}/IMG_9917.HEIC" data-heic="{{ travel_images }}/IMG_9917.HEIC" alt="旅遊照片 11" loading="lazy">
  </button>
  <figcaption>旅遊照片相簿</figcaption>
</figure>

<div class="album-modal" hidden>
  <div class="album-modal__backdrop" data-album-close></div>
  <div class="album-modal__content" role="dialog" aria-modal="true" aria-label="放大檢視照片">
    <button class="album-modal__close" type="button" data-album-close aria-label="關閉照片">×</button>
    <img class="album-modal__image" alt="">
  </div>
</div>

<style>
  .photo-button {
    background: none;
    border: 0;
    padding: 0;
    cursor: zoom-in;
    width: 100%;
    display: inline-block;
    margin: 0;
  }

  .album-grid {
    max-width: 960px;
    margin: 32px auto 0;
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 16px;
  }

  .album-grid .photo-button img {
    width: 100%;
    height: auto;
    display: block;
    border-radius: 12px;
    box-shadow: 0 10px 24px rgba(0, 0, 0, 0.15);
    object-fit: cover;
  }

  @media (max-width: 1024px) {
    .album-grid {
      max-width: 720px;
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }

  @media (max-width: 640px) {
    .album-grid {
      max-width: 100%;
      grid-template-columns: 1fr;
    }
  }

  .album-modal[hidden] {
    display: none;
  }

  .album-modal {
    position: fixed;
    inset: 0;
    z-index: 9999;
  }

  .album-modal__backdrop {
    position: absolute;
    inset: 0;
    background: rgba(0, 0, 0, 0.75);
  }

  .album-modal__content {
    position: absolute;
    inset: 5%;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .album-modal__image {
    max-width: 90vw;
    max-height: 90vh;
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.4);
    border-radius: 8px;
  }

  .album-modal__close {
    position: absolute;
    top: 12px;
    right: 16px;
    z-index: 2;
    background: rgba(255, 255, 255, 0.95);
    color: #111;
    border: 1px solid rgba(0, 0, 0, 0.1);
    border-radius: 999px;
    width: 36px;
    height: 36px;
    font-size: 24px;
    cursor: pointer;
    box-shadow: 0 6px 16px rgba(0, 0, 0, 0.2);
  }
</style>

<script src="https://cdn.jsdelivr.net/npm/heic2any/dist/heic2any.min.js"></script>
<script>
  document.addEventListener("DOMContentLoaded", () => {
    if (!window.heic2any) {
      return;
    }

    document.querySelectorAll(".heic-photo").forEach(async (img) => {
      if (img.dataset.converted) {
        return;
      }

      try {
        const response = await fetch(img.dataset.heic);
        const buffer = await response.arrayBuffer();
        const convertedBlob = await window.heic2any({
          blob: new Blob([buffer]),
          toType: "image/jpeg",
          quality: 0.85,
        });
        const blobUrl = URL.createObjectURL(convertedBlob);
        img.src = blobUrl;
        img.dataset.converted = "true";
      } catch (error) {
        console.warn("HEIC conversion failed", error);
      }
    });
  });
</script>

<script>
  document.addEventListener("DOMContentLoaded", () => {
    const modal = document.querySelector(".album-modal");
    const modalImage = modal?.querySelector(".album-modal__image");
    const closeTargets = modal?.querySelectorAll("[data-album-close]") ?? [];

    if (!modal || !modalImage) {
      return;
    }

    document.querySelectorAll(".photo-button img").forEach((img) => {
      img.addEventListener("click", () => {
        modalImage.src = img.currentSrc || img.src;
        modalImage.alt = img.alt;
        modal.hidden = false;
        document.body.style.overflow = "hidden";
      });
    });

    closeTargets.forEach((target) => {
      target.addEventListener("click", () => {
        modal.hidden = true;
        modalImage.src = "";
        document.body.style.overflow = "";
      });
    });

    document.addEventListener("keydown", (event) => {
      if (event.key === "Escape" && !modal.hidden) {
        modal.hidden = true;
        modalImage.src = "";
        document.body.style.overflow = "";
      }
    });
  });
</script>
