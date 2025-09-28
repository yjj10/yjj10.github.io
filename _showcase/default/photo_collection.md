---
show: false
width: 6
date: 2015-09-28 00:01:00 +0800
height: 400px
images:
 src="{{ 'assets/images/travel/IMG_3570.JPG' | relative_url }}" class="img-fluid rounded-xl" >
  
{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
