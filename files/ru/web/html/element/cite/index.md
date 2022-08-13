---
title: <cite>
slug: Web/HTML/Element/cite
tags:
  - HTML
  - Источник
  - Цитата
  - Элемент
translation_of: Web/HTML/Element/cite
---
<h2 id="Описание">Описание</h2>

<p><strong>HTML-элемент &lt;cite&gt;</strong> (<em>от англ. Citation</em>) представляет из себя ссылку на источник цитаты. Он должен включать в себя название произведения или URL, который может быть в сокращённом виде в соответствии с правилами, используемых для добавления метаданных цитирования.</p>

<div class="note">
<p><strong>Об использовании:</strong></p>

<ul>
 <li>Творческая работа может включать в себя книгу, статью, очерк, стихотворение, суждение, песню, сценарий, фильм, ТВ-шоу, игру, скульптуру, живопись, театральную постановку, пьесу, оперу, мюзикл, выставку, юридический отчёт, компьютерную программу, веб-сайт, веб-страницу, сообщение или комментарий в блоге или на форуме, tweet, письменное или устное заявление и так далее.</li>
 <li>Спецификация W3C утверждает, что ссылка на творческую работу может содержать имя автора, в то время, как WHATWG заявляет, что она не может включать имя человека ни в коем случае.</li>
 <li>Используйте атрибут {{htmlattrxref("cite", "blockquote")}} элемента {{HTMLElement("blockquote")}} или элемента {{HTMLElement("q")}} для ссылки на интернет-ресурс источника.</li>
</ul>
</div>

<table class="properties">
 <tbody>
  <tr>
   <th scope="row"><a href="/en-US/docs/HTML/Content_categories" title="HTML/Content_categories">Content categories</a></th>
   <td><a href="/en-US/docs/HTML/Content_categories#Flow_content" title="HTML/Content categories#Flow content">Flow content</a>, <a href="/en-US/docs/HTML/Content_categories#Phrasing_content" title="HTML/Content categories#Phrasing content">phrasing content</a>, palpable content.</td>
  </tr>
  <tr>
   <th scope="row">Permitted content</th>
   <td><a href="/en-US/docs/HTML/Content_categories#Phrasing_content" title="HTML/Content_categories#Phrasing_content">Phrasing content</a>.</td>
  </tr>
  <tr>
   <th scope="row">Tag omission</th>
   <td>{{no_tag_omission}}</td>
  </tr>
  <tr>
   <th scope="row">Permitted parent elements</th>
   <td>Any element that accepts <a href="/en-US/docs/HTML/Content_categories#Phrasing_content" title="HTML/Content_categories#Phrasing_content">phrasing content</a>.</td>
  </tr>
  <tr>
   <th scope="row">DOM interface</th>
   <td>{{domxref("HTMLElement")}} Up to Gecko 1.9.2 (Firefox 4) inclusive, Firefox implements the {{domxref("HTMLSpanElement")}} interface for this element.</td>
  </tr>
 </tbody>
</table>

<h2 id="Атрибуты">Атрибуты</h2>

<p>Для данного элемента доступны только <a href="/en-US/docs/HTML/Global_attributes" title="HTML/Global attributes">глобальные атрибуты</a>.</p>

<h2 id="Пример">Пример</h2>

<pre class="brush: html">More information can be found in &lt;cite&gt;[ISO-0000]&lt;/cite&gt;</pre>

<p>{{EmbedLiveSample('Пример')}}</p>

<h2 id="Примечание">Примечание</h2>

<p>To avoid the default italic style from being used for the &lt;cite&gt; element use the <a href="/en-US/docs/CSS" title="CSS">CSS</a> {{cssxref("font-style")}} property.</p>

<h2 id="Specifications">Спецификации</h2>

{{Specifications}}

<h2 id="Поддержка_браузерами">Поддержка браузерами</h2>

<p>{{Compat}}</p>

<h2 id="sect1"></h2>

<h2 id="Смотрите_также">Смотрите также</h2>

<ul>
 <li>Элемент {{HTMLElement("blockquote")}} для длинных цитат.</li>
 <li>Элемент {{HTMLElement("q")}} для встраиваемых цитат.</li>
</ul>

<div>{{HTMLRef}}</div>