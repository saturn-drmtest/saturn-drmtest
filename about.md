---
layout: page
titles:
  # @start locale config
  en      : &EN       About
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN
  zh-Hans : &ZH_HANS  关于
  zh      : *ZH_HANS
  zh-CN   : *ZH_HANS
  zh-SG   : *ZH_HANS
  zh-Hant : &ZH_HANT  關於
  zh-TW   : *ZH_HANT
  zh-HK   : *ZH_HANT
  ko      : &KO       소개
  ko-KR   : *KO
  fr      : &KO       À propos
  fr-BE   : *FR
  fr-CA   : *FR
  fr-CH   : *FR
  fr-FR   : *FR
  fr-LU   : *FR
  # @end locale config
key: page-about
show_title: false
permalink: /about.html
show_edit_on_github: false
show_date: false
show_tags: false
comment: false
lightbox: false
comment: false
---

<section class="info">
  <h1 id="page_title">About Me</h1>

  <div class="author_profile">
    {%- assign _author = site.author -%}
    {%- include article/footer/author-profile.html author=_author -%}
  </div>

</section>

[My Resume](./assets/ZihanMEI_Resume.pdf)

[My Portfolio](./assets/ZihanMEI_Portfolio.pdf)