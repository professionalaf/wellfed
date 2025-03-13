---
layout: home
title: WellFed
hero_title: Nourish Your Next Chapter
hero_subtitle: Supporting Federal workers transitioning to the private sector
hero_button_text: Learn More
hero_button_url: /about/
featured_sections:
  - title: Our Mission
    description: WellFed is dedicated to supporting Federal Government workers who have lost their jobs or are transitioning to the private sector with resources, training, and community.
    button_text: Read More
    button_url: /about/
  - title: Upcoming Events
    description: Join us for networking events, career workshops, and skill-building sessions designed to empower your transition to the private sector.
    button_text: View Calendar
    button_url: /events/
  - title: Get Involved
    description: Connect with us to access resources, join our community, or partner with us to support Federal workers in transition.
    button_text: Contact Us
    button_url: /contact/
---

## Welcome to WellFed

WellFed is dedicated to supporting Federal workers through career transitions. Whether you've recently lost your government position or are planning a move to the private sector, we're here to provide the resources, community, and opportunities you need to thrive in your next chapter.

## What We Do

Our programs are tailored specifically for Federal employees navigating career changes. Through job training workshops, networking events, resume clinics, and career counseling, we empower former government workers with the skills and connections needed to succeed in the private sector. We understand the unique challenges of this transition and are here to help you every step of the way.

## Latest News

{% for post in site.posts limit:3 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %} 