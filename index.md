---
title: Home
---

# Long-term Personalization in HRI.


{% include figure.html img="uidaho-workshop.jpg" alt="intro image here" caption="Library workshop" width="75%" %}

A minimal Jekyll theme for creating workshop websites.

*Add your workshop abstract here!*

## Provisional Schedule

The proposed schedule is subject to change depending on the number of submissions. It will be
re-arranged to synchronize with the lunch and coffee breaks.

- 9:00 - 9:05 Opening remarks
- 9:05 - 9:35 Keynote #1
- 9:35 - 10:05 Keynote #2
- 10:05 - 10:45 Brain-storming #1
- 10:45 - 11:05 Coffee break
- 11:05 - 12:20 Full talks (4-5 papers)
- 12:20 - 13:50 Lunch
- 13:50 - 14:20 Keynote #3
- 14:20 - 14:50 Keynote #4
- 14:50 - 15:20 Short talks (5-6 papers)
- 15:20 - 15:40 Coffee break
- 15:40 - 17:00 Full talks (4-5 papers)
- 17:00 - 17:45 Brain-storming #2
- 17:45 - 18:00 Closing remarks
- 18:00 - Workshop dinner

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

Hosted by [Github Pages](https://pages.github.com/), {{ site.pub_year }}.
