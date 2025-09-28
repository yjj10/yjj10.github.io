---
show: true
width: 12              # 占满一行；如果想跟猫卡一样宽可改成 3 或 4
date: 2020-01-01 00:01:00 +0800   # 给个更“旧”的时间，这样会排在 Cats 现有卡片之后
group: Cats            # 关键：并入 Cats 分组
title: Travel          # 这里只是卡片内部的小标题，不会再生成新的大组标题
---

<div class="p-3">
  <h5 class="card-title mb-3">Travel</h5>
  <div class="row">

  <div class="col-12 col-sm-6 col-md-4 col-lg-3 mb-3">
      <img
        data-src="{{ '/assets/images/travel/norway.jpg' | relative_url }}"
        src="{{ '/assets/images/empty_300x200.png' | relative_url }}"
        class="lazy w-100 rounded-xl"
        alt="Norway">
    </div>

  <div class="col-12 col-sm-6 col-md-4 col-lg-3 mb-3">
      <img
        data-src="{{ '/assets/images/travel/london.jpg' | relative_url }}"
        src="{{ '/assets/images/empty_300x200.png' | relative_url }}"
        class="lazy w-100 rounded-xl"
        alt="London">
    </div>

   <div class="col-12 col-sm-6 col-md-4 col-lg-3 mb-3">
      <img
        data-src="{{ '/assets/images/travel/kyoto.jpg' | relative_url }}"
        src="{{ '/assets/images/empty_300x200.png' | relative_url }}"
        class="lazy w-100 rounded-xl"
        alt="Kyoto">
    </div>

  <div class="col-12 col-sm-6 col-md-4 col-lg-3 mb-3">
      <img
        data-src="{{ '/assets/images/travel/paris.jpg' | relative_url }}"
        src="{{ '/assets/images/empty_300x200.png' | relative_url }}"
        class="lazy w-100 rounded-xl"
        alt="Paris">
    </div>

   <div class="col-12 col-sm-6 col-md-4 col-lg-3 mb-3">
      <img
        data-src="{{ '/assets/images/travel/italy.jpg' | relative_url }}"
        src="{{ '/assets/images/empty_300x200.png' | relative_url }}"
        class="lazy w-100 rounded-xl"
        alt="Italy">
    </div>

  </div>
</div>
