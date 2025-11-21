---
layout: default
title: Dashboard
---

# HYRAHMO

**Media • Quant • Code • Gaming**

От тактик в CS до алгоритмов в Quant Trading.  
Я создаю видео, пишу код и исследую мир.

<!-- КНОПКА-ЯКОРЬ (Ведет вниз) -->
<a href="#directory" class="clean-btn" style="border: 1px solid var(--border); padding: 5px 10px; border-radius: 4px; font-size: 0.8rem; display: inline-block; margin-top: 10px;">
  📂 Архив страниц ↓
</a>
<a href="wiki.hyrahmo.ru" target="_blank" class="link-btn major-link">
  📂 YouTube ↓
</a>
---

## Разделы

<div class="nav-grid">
  
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
    <strong>Link Hub</strong>
  </a>
</div>

## Connect

<div class="matrix-grid">
  <a href="https://youtube.com/@hyrahmo" target="_blank" class="link-btn major-link">YouTube</a>
  <a href="https://t.me/hyrahmo" target="_blank" class="link-btn major-link">Telegram</a>
  <a href="https://github.com/hyrahmo" target="_blank" class="link-btn major-link">GitHub</a>
  <a href="mailto:contact@hyrahmo.com" class="link-btn major-link">Email</a>
</div>

<br>
<br>

<!-- ЯКОРЬ ДЛЯ ПРОКРУТКИ -->
<div id="directory"></div>

## Все страницы
<p style="font-size: 0.9rem; opacity: 0.6;">Полный список файлов в системе:</p>

<div class="auto-list">
  {% for page in site.pages %}
    {% if page.title and page.url != "/" and page.url != "/404.html" %}
      <a href="{{ page.url }}" class="auto-link">
        <span>{{ page.title }}</span>
        <span style="opacity: 0.5; font-family: monospace;">DIR ↗</span>
      </a>
    {% endif %}
  {% endfor %}
</div>
