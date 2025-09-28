---
show: false
width: 12                       # 占整行
date: 2025-01-01 00:01:00 +0800 # 比旧卡片时间新；它会排在“Cats”卡片后/前，按你的其他卡片日期决定
title: Travel Moments           # 卡片抬头（会显示在卡片左上角）
---

<div class="p-3">
  <div class="d-flex align-items-center mb-2">
    <h5 class="mb-0">Travel Moments</h5>
    <div class="ml-3">
      <span class="badge badge-primary mr-1">Norway</span>
      <span class="badge badge-primary mr-1">London</span>
      <span class="badge badge-primary mr-1">Kyoto</span>
      <span class="badge badge-primary mr-1">Paris</span>
      <span class="badge badge-primary">Italy</span>
    </div>
  </div>

  <!-- 直接 src 出图：不走懒加载，马上显示 -->
  <div class="row no-gutters">
    <div class="col-12 col-sm-6 col-md-4 col-lg-3 p-2">
      <img src="{{ '/assets/images/travel/norway.jpg' | relative_url }}"
           alt="Norway" class="img-fluid rounded-xl shadow-sm">
    </div>
    <div class="col-12 col-sm-6 col-md-4 col-lg-3 p-2">
      <img src="{{ '/assets/images/travel/london.jpg' | relative_url }}"
           alt="London" class="img-fluid rounded-xl shadow-sm">
    </div>
    <div class="col-12 col-sm-6 col-md-4 col-lg-3 p-2">
      <img src="{{ '/assets/images/travel/kyoto.jpg' | relative_url }}"
           alt="Kyoto" class="img-fluid rounded-xl shadow-sm">
    </div>
    <div class="col-12 col-sm-6 col-md-4 col-lg-3 p-2">
      <img src="{{ '/assets/images/travel/paris.jpg' | relative_url }}"
           alt="Paris" class="img-fluid rounded-xl shadow-sm">
    </div>
    <div class="col-12 col-sm-6 col-md-4 col-lg-3 p-2">
      <img src="{{ '/assets/images/travel/italy.jpg' | relative_url }}"
           alt="Italy" class="img-fluid rounded-xl shadow-sm">
    </div>
  </div>
</div>
