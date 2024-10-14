# 티웨이 하늘체

[배포처 바로가기](https://www.twayair.com/app/serviceInfo/contents/1320)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Tway Sky`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/TwaySky/TwaySky.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/TwaySky/TwaySky.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Tway Sky';
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/TwaySky/TwaySky.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TwaySky/TwaySky.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TwaySky/TwaySky.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/TwaySky/subsets/TwaySky-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/TwaySky/subsets/TwaySky-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Tway Sky", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
티웨이 항공체,하늘체,날다체 폰트의 지적 재산권을 포함한 모든 권리는 “㈜티웨이항공”에 있습니다. 
이 폰트는 개인 및 기업사용자를 포함한 모든 사용자에게 무료로 제공합니다. 
이 폰트를 유료로 판매하는 것은 금지하며 폰트는 수정 및 재배포를 할수있으나 폰트자체의 원본파일은 수정불가합니다. 
배포되는 형태 그대로 사용을 권장합니다. 
당사의 이미지를 훼손할 수 있는 불법사이트나 허위과장광고, 기타 공서양속에 반하는 인쇄/광고물에 사용을 금지합니다.
```
