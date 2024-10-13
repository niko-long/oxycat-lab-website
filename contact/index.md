---
title:  JOIN US
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

<!-- 引入 Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">

### Interested in Joining Us?
We are always looking for talented individuals to join our team. Check out our [Open Positions](#) or send us your CV.
{%
  include button.html
  text="Submit your CV"
  link="mailto:recruitment@oxycat-lab.com"
%}


{%
  include button.html
  type="email"
  text="f.hollmann@tudelft.nl"
  link="f.hollmann@tudelft.nl"
%}
{%
  include button.html
  type="phone"
  text="+31 15 2781957"
  link="+31 15 2781957"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/TNW+Applied+Sciences+TU+Delft/@51.9902551,4.3772096,1372m/data=!3m2!1e3!4b1!4m6!3m5!1s0x47c5b586e8676331:0x4540bc8bd4b7790c!8m2!3d51.9902551!4d4.3797845!16s%2Fg%2F11cn9f5sl3?entry=ttu&g_ep=EgoyMDI0MTAwOS4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}
### Meet Our Team

 <img src="../images/team2.jpg" class="d-block w-100" alt="Team Member 2">

  

{% include section.html %}


{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
