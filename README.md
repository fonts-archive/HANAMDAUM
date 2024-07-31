# 하남다움체

[배포처 바로가기](https://www.hanam.go.kr/www/contents.do?key=7660)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `HANAMDAUM`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/HANAMDAUM/HANAMDAUM.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/HANAMDAUM/HANAMDAUM.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'HANAMDAUM';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/HANAMDAUM/HANAMDAUM-Body.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HANAMDAUM/HANAMDAUM-Body.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HANAMDAUM/HANAMDAUM-Body.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HANAMDAUM/HANAMDAUM-Body.ttf') format('truetype');
}
@font-face {
    font-family: 'HANAMDAUM';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/HANAMDAUM/HANAMDAUM-Title.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HANAMDAUM/HANAMDAUM-Title.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HANAMDAUM/HANAMDAUM-Title.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HANAMDAUM/HANAMDAUM-Title.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/HANAMDAUM/subsets/HANAMDAUM-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/HANAMDAUM/subsets/HANAMDAUM-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "HANAMDAUM", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
하남다움체는 공공누리 제1유형 기준 무료로 자유롭게 사용 가능합니다. 
단, 상업적으로 재판매하는 행위는 제한됨을 알려드립니다.
```
