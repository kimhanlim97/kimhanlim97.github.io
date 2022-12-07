---
layout: default
title: HTML 메타데이터 태그
parent: Head Element
nav_order: 1
---
## head 태그

`head` 태그는 웹 브라우저가 해석해야할 웹 페이지의 제목, 설명, 사용할 파일 위치, 스타일 같은 사용자에게 보이지 않는 웹페이지의 보이지 않는 정보(메타데이터)를 포함합니다. MDN에서는 `head` 태그에 포함되는 정보를 machine readable information이라고 정의합니다.

## 메타데이터 태그

`title` 태그는 HTML 문서의 제목을 정의하는 태그입니다. 웹 브라우저의 탭에 표시됩니다.

```html
<head>
	<title>HanLim</title>
</head>
```

`link` 태그는 외부 문서를 HTML 문서와 연결할 때 사용합니다. 주로 웹페이지의 로고(favicon)를 지정하거나 외부 CSS 문서(stylesheet)를 지정할 때 사용합니다. 해당 태그의 속성 `rel`과 `href`는 각각 가져올 문서와의 관계, 가져올 문서의 경로를 표시할 때 쓰입니다.

```html
<head>
	<link rel="stylesheet" href="./main.css"/>
	<link rel="icon" href="./favicon.png"/>
</head>
```

`style` 태그는 HTML 문서 안에서 스타일을 정의할 때 사용되는 태그입니다.

```html
<head>
	<style>
		div {
			color: red;
		}
	</style>
</head>
```

`script` 태그는 웹페이지의 동작을 정의할 때 사용되는 태그입니다. `src` 속성에 경로를 지정하여 외부 자바스크립트 파일을 참조할 수도 있고, 만약 해당 속성을 지정하지 않았을 경우 `style` 태그와 유사하게 내부에 자바스크립트 코드를 작성하여 웹페이지의 동작을 정의할 수도 있습니다.

```html
<head>
	<script src="./main.js"></script>
	<script>
		alert('Hello World!')
	</script>
</head>
```

`meta` 태그는 `link`, `script`, `style`, `title`과 같은 다른 메타 관련 태그로 나타낼 수 없는 메타 데이터를 표현할 때 사용됩니다. 주로 HTML 문서의 제작자, 내용, 키워드 같은 여러 정보를 검색엔진이나 브라우저에게 제공할 때 쓰입니다.

```html
<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```