---
title: Home
---

# Workshop on Understanding, Mitigating, and Leveraging Cognitive Biases to Calibrate Trust in Evolving AI Systems

{% include figure.html img="uidaho-workshop.jpg" alt="intro image here" caption="Library workshop" width="75%" %}

Despite decades of advancements in Artificial Intelligence (AI), fostering appropriate trust in AI systems remains a challenge. Cognitive biases — systematic deviations from rational judgement — profoundly influence human decision-making, and reliance on such "mental shortcuts" can make AI systems appear more or less trustworthy than they really are, often undermining collaboration outcomes. As AI evolves with more sophisticated and persuasive natural language outputs, particularly through Generative AI (GenAI) and Large Language Models (LLMs), these biases may manifest in new and unpredictable ways, calling for their comprehensive examination. This workshop builds on a series of prior workshops at [CSCW '23](https://dl.acm.org/doi/abs/10.1145/3584931.3611284), [Dagstuhl Seminar 22172](https://www.dagstuhl.de/seminars/seminar-calendar/seminar-details/22172), [CHI '21](https://dl.acm.org/doi/abs/10.1145/3411763.3441350), and [CHI '20](https://dl.acm.org/doi/abs/10.1145/3334480.3375159), which examined the design of technologies that support human cognition and decision-making through the lens of cognitive biases. While these earlier workshops established the importance of recognising biases in decision-making, this proposed workshop extends the conversation to the specific and timely context of trust calibration in AI systems, particularly in light of emerging paradigms such as Generative AI and LLMs. As a specialised extension, it represents the continuation of an established HCI research agenda, while also advancing it to proactively shape how cognitive biases are understood, mitigated, and leveraged in the design of trustworthy AI systems.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

Hosted by [University of Idaho Library](http://www.lib.uidaho.edu/), {{ site.pub_year }}.
 
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
