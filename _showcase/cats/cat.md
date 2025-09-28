<style>
  .travel-grid{
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
    gap: 12px;
  }
  .travel-grid img{
    width: 100%;
    height: 240px;            /* 卡片统一高度，避免长图太高 */
    object-fit: cover;        /* 居中裁切，铺满区域 */
    border-radius: 1rem;      /* 圆角和模板统一 */
  }
</style>

<div class="travel-grid">
  <img src="{{ '/assets/images/travel/IMG_3550.jpg' | relative_url }}" alt="travel 1">
  <img src="{{ '/assets/images/travel/IMG_3552.jpg' | relative_url }}" alt="travel 2">
  <img src="{{ '/assets/images/travel/IMG_3568.jpg' | relative_url }}" alt="travel 3">
  <img src="{{ '/assets/images/travel/IMG_3569.jpg' | relative_url }}" alt="travel 4">
  <!-- 想继续加图，按同样格式往下加即可 -->
</div>
