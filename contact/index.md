---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact



{%
  include button.html
  type="email"
  text="gikwon@inha.ac.kr"
  link="gikwon@inha.ac.kr"
%}
{%
  include button.html
  type="phone"
  text="(032) 860-8373"
  link="+82-032-860-8373"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/%EC%9D%B8%ED%95%98%EB%8C%80%ED%95%99%EA%B5%90+%ED%95%98%EC%9D%B4%ED%85%8C%ED%81%AC%EC%84%BC%ED%84%B0/data=!3m1!4b1!4m6!3m5!1s0x357b79aa055402f5:0x6a02b6b2d7501325!8m2!3d37.4505988!4d126.6573096!16s%2Fg%2F11kj8_tglg?entry=ttu"
%}

{% include section.html %}


{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
#### Professor's Office  
Hi-Tech 1109(하이테크센터 1109호)
{% endcapture %}

{% capture col2 %}
#### Computer Network Lab
Hi-Tech 1107(하이테크센터 1107호)
{% endcapture %}

{% capture col3 %}
#### Lab Representative's Phone Number
010-1111-1111
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
