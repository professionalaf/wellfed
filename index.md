---
layout: home
title: WellFed
hero_title: Nourish Your Next Chapter
hero_subtitle: Providing healthy meals and nutrition education for every stage of life
hero_button_text: Learn More
hero_button_url: /about/
featured_sections:
  - title: Our Mission
    description: WellFed is dedicated to ensuring everyone has access to nutritious meals that support health and wellbeing at every stage of life.
    button_text: Read More
    button_url: /about/
  - title: Upcoming Events
    description: Join us for community gatherings, cooking classes, and nutrition workshops designed to inspire and educate.
    button_text: View Calendar
    button_url: /events/
  - title: Get Involved
    description: Volunteer, donate, or partner with us to help make nutritious food accessible to everyone in our community.
    button_text: Contact Us
    button_url: /contact/
---

## Welcome to WellFed

WellFed is committed to nourishing communities through thoughtfully prepared meals and nutrition education. We believe that good food is the foundation of health and wellbeing, and we're passionate about making it accessible to everyone.

## What We Do

Our programs cater to various life stages and needs, from new parents adjusting to life with a baby to seniors looking to maintain their health and independence. Through meal delivery services, cooking classes, and community events, we're building a healthier, more connected community.

## Latest News

{% for post in site.posts limit:3 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %} 