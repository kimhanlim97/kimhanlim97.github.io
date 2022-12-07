---
layout: default
title: HTML이란?
nav_order: 1

---
## HTML이란?

HTML은 다양한 요소(Element)들을 통해 웹페이지와 컨텐츠의 구조를 정의할 때 사용되는 언어입니다. 때문에 HTML은 프로그래밍 언어라기보다는 마크업 언어라고 보는 것이 조금 더 타당합니다. 

## HTML Element

HTML 요소(Element)의 가장 일반적인 형태는 시작 태그와 종료 태그 그리고 태그 사이에 위치한 컨텐츠로 구성되어 있습니다. 

```html
<p>Hello</p>
```

또한 HTML 요소들은 각각 속성(Attribute)을 가질 수도 있습니다. HTML 속성이란 요소의 성질, 특징을 정의하는 명세이며 요소에 추가적인 정보를 제공합니다. 속성은 시작 태그에 위치해야 하며 이름과 값의 쌍을 이루는 형태로 작성됩니다.

```html
<img src="html.jpg" width="104" height="142">
```

HTML 요소들은 컨텐츠 뿐만 아니라 각각의 HTML 요소들을 포함할 수 있으며 어떤 요소안에 포함된 요소를 자식 요소라고도 합니다. 반대로 자식 요소를 포함한 요소를 부모 요소라고 합니다.

```html
<p><strong>Hello</strong></p>
```

또한 어떤 HTML 요소들은 시작 태그와 종료 태그를 명시하여 작성할 필요가 없는 경우도 있습니다. 즉, 컨텐츠를 포함할 필요가 없는 태그도 있습니다. 이러한 태그를 빈 태그라고 합니다.

```html
<img src="images/firefox-icon.png" alt="My test image">
```