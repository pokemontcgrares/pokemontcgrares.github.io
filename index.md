---
layout: default
---

A simple list of **errors**, **misprints**, **alternates**, and **mistakes** appearing in the Pokemon Trading Card Game (TGC). This list only includes instances where mistakes were corrected, meaning a sense of _rarity_ exists. The goal is to document the rare instance, which is not always the instance that contains the mistake. Lore and an explanation, as well as a sense of _rarity_ for the cards is attempted.

{% capture cards %}{% include_relative cards.md %}{% endcapture %}
{{ cards | markdownify }}

{% capture footer %}{% include_relative footer.md %}{% endcapture %}
{{ footer | markdownify }}