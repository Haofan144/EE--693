---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

Lecture{: .label .label-purple }: Lectures given by professor. 
Presentation{: .label .label-green }: Presentations given by students. 
TBD{: .label .label-blue }: Can be either lecture or presentation. 

{% for module in site.modules %}
{{ module }}
{% endfor %}
