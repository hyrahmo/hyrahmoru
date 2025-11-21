---
layout: default
title: Dashboard
---

# HYRAHMO

**Media • Quant • Code • Gaming**

От тактик в CS до алгоритмов в Quant Trading.  
Я создаю видео, пишу код, занимаюсь инвестициями и исследую мир.

---

## Разделы

<div class="nav-grid">
  <!-- Ты можешь менять эти кнопки вручную здесь -->
  
  <a href="/media" class="nav-card">
    <span>01.</span>
    <strong>Медиа & Бизнес</strong>
  </a>
  
  <a href="/cs" class="nav-card">
    <span>02.</span>
    <strong>Code & CS</strong>
  </a>
  
  <a href="/physics" class="nav-card">
    <span>03.</span>
    <strong>Science</strong>
  </a>

   <a href="/links" class="nav-card">
    <span>04.</span>
    <strong>Все ссылки</strong>
  </a>
</div>

<!-- Здесь будут соцсети -->
## Connect

<div class="matrix-grid">
  <a href="https://youtube.com/@hyrahmo" target="_blank" class="link-btn major-link">YouTube</a>
  <a href="https://t.me/hyrahmo" target="_blank" class="link-btn major-link">Telegram</a>
  <a href="https://github.com/hyrahmo" target="_blank" class="link-btn major-link">GitHub</a>
  <a href="mailto:contact@hyrahmo.com" class="link-btn major-link">Email</a>
</div>

<br>

<!-- АВТОМАТИЧЕСКИЙ СПИСОК ВСЕХ СТРАНИЦ -->
## Index / Все Страницы

<div class="auto-list">
  {% for page in site.pages %}
    {% if page.title and page.url != "/" and page.url != "/404.html" %}
      <a href="{{ page.url }}" class="auto-link">
        <span>{{ page.title }}</span>
        <span style="opacity: 0.5;">↗</span>
      </a>
    {% endif %}
  {% endfor %}
</div>
