---
layout: page
title: LLM4Sec 
permalink: /llm4sec/
description: Publications related to <strong>LLMs for cybersecurity</strong>.
---

<div style="text-align: center; margin: 2em 0;">
  <img src="/assets/img/llm4sec_banner.png" alt="LLM4Sec Banner" style="max-width: 420px; width: 100%; border-radius: 16px;">
</div>

<div class="publications">
  {% bibliography --group_by none --query @*[llm4sec=true]* %}
</div>
