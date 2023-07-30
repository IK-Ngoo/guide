---
layout: main
title: 按鈕及連結
iframe_page: ""
---

### 按鈕類別

{% capture html %}{% include ctas/button.html %}{% endcapture %}
{% include example.html content=html %}

#### CSS

- `.button`：作為全部按鈕的基底。
- `.button-primary`：作為主要或正面的動作視覺傳達。

### 按鈕尺寸

{% capture html %}{% include ctas/button-size.html %}{% endcapture %}
{% include example.html content=html %}

#### CSS

- `.button-large`：大按鈕。
- `.button-small`：小按鈕。
- `.button-tiny`：迷你按鈕。

### 連結

{% capture html %}{% include ctas/link.html %}{% endcapture %}
{% include example.html content=html %}

#### CSS

- 無。

#### 親和力

- 連結與文字必須用非顏色的方式做區分。一般網頁連結皆使用底線作為標注。見 Failure of [Success Criterion 1.4.1](https://w3c.github.io/wcag/understanding/use-of-color.html) due to [creating links that are not visually evident without color vision](https://www.w3.org/WAI/WCAG22/Techniques/failures/F73)