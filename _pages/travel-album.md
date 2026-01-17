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

若你的瀏覽器暫時不支援 HEIC 格式，本頁會嘗試自動轉成可顯示的格式，讓你可以正常瀏覽每張照片。

<figure class="third">
  <a href="/assets/images/travel/IMG_0074.HEIC"><img class="heic-photo" src="/assets/images/travel/IMG_0074.HEIC" data-heic="/assets/images/travel/IMG_0074.HEIC" alt="旅遊照片 1" loading="lazy"></a>
  <a href="/assets/images/travel/IMG_0104.HEIC"><img class="heic-photo" src="/assets/images/travel/IMG_0104.HEIC" data-heic="/assets/images/travel/IMG_0104.HEIC" alt="旅遊照片 2" loading="lazy"></a>
  <a href="/assets/images/travel/IMG_0286.HEIC"><img class="heic-photo" src="/assets/images/travel/IMG_0286.HEIC" data-heic="/assets/images/travel/IMG_0286.HEIC" alt="旅遊照片 3" loading="lazy"></a>
  <a href="/assets/images/travel/IMG_0554.HEIC"><img class="heic-photo" src="/assets/images/travel/IMG_0554.HEIC" data-heic="/assets/images/travel/IMG_0554.HEIC" alt="旅遊照片 4" loading="lazy"></a>
  <a href="/assets/images/travel/IMG_0908.HEIC"><img class="heic-photo" src="/assets/images/travel/IMG_0908.HEIC" data-heic="/assets/images/travel/IMG_0908.HEIC" alt="旅遊照片 5" loading="lazy"></a>
  <a href="/assets/images/travel/IMG_1150.HEIC"><img class="heic-photo" src="/assets/images/travel/IMG_1150.HEIC" data-heic="/assets/images/travel/IMG_1150.HEIC" alt="旅遊照片 6" loading="lazy"></a>
  <a href="/assets/images/travel/IMG_1159.HEIC"><img class="heic-photo" src="/assets/images/travel/IMG_1159.HEIC" data-heic="/assets/images/travel/IMG_1159.HEIC" alt="旅遊照片 7" loading="lazy"></a>
  <a href="/assets/images/travel/IMG_9261.HEIC"><img class="heic-photo" src="/assets/images/travel/IMG_9261.HEIC" data-heic="/assets/images/travel/IMG_9261.HEIC" alt="旅遊照片 8" loading="lazy"></a>
  <a href="/assets/images/travel/IMG_9350.HEIC"><img class="heic-photo" src="/assets/images/travel/IMG_9350.HEIC" data-heic="/assets/images/travel/IMG_9350.HEIC" alt="旅遊照片 9" loading="lazy"></a>
  <a href="/assets/images/travel/IMG_9749.HEIC"><img class="heic-photo" src="/assets/images/travel/IMG_9749.HEIC" data-heic="/assets/images/travel/IMG_9749.HEIC" alt="旅遊照片 10" loading="lazy"></a>
  <a href="/assets/images/travel/IMG_9917.HEIC"><img class="heic-photo" src="/assets/images/travel/IMG_9917.HEIC" data-heic="/assets/images/travel/IMG_9917.HEIC" alt="旅遊照片 11" loading="lazy"></a>
  <figcaption>旅遊照片相簿</figcaption>
</figure>

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

## 相簿連結

- [旅遊照片 1](/assets/images/travel/IMG_0074.HEIC)
- [旅遊照片 2](/assets/images/travel/IMG_0104.HEIC)
- [旅遊照片 3](/assets/images/travel/IMG_0286.HEIC)
- [旅遊照片 4](/assets/images/travel/IMG_0554.HEIC)
- [旅遊照片 5](/assets/images/travel/IMG_0908.HEIC)
- [旅遊照片 6](/assets/images/travel/IMG_1150.HEIC)
- [旅遊照片 7](/assets/images/travel/IMG_1159.HEIC)
- [旅遊照片 8](/assets/images/travel/IMG_9261.HEIC)
- [旅遊照片 9](/assets/images/travel/IMG_9350.HEIC)
- [旅遊照片 10](/assets/images/travel/IMG_9749.HEIC)
- [旅遊照片 11](/assets/images/travel/IMG_9917.HEIC)
