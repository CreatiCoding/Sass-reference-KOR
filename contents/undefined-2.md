---
description: 'https://www.kaelig.fr/bettersassdocs/#syntax'
---

# 구문

Sass 에는 두 가지 구문을 이용할 수 있습니다.

 첫 번째는 이 문서에서 다뤄지는 CSS 문법의 확장인 SCSS\(Sassy CSS\)입니다. 이는 모든 올바른 CSS 스타일 시트는  동일한 의미를 가진 SCSS 파일임을 의미합니다. 또한, SCSS는  대부분의 CSS 핵과 vendor 마다의 문법\(IE의 오래된 filter 문법\)을 이해합니다. 이 SCSS는 아래 묘사되는 Sass의 기능으로 향상됩니다. 이 구문을 사용하는 파일의 확장자는 `.scss`입니다.

 두 번째는 들여쓰여진 구문으로 알려진 오래된 구문\(그냥 'Sass"라고도 알려진\)으로, CSS 작성을 좀 더 간결하게 만들어줍니다. 선택자의 중첩을 가리킬 땐 중괄호 대신 들여쓰기를 사용하고 속성을 구분할 땐 세미클론 대신 개행을 사용합니다. 가끔 사람들은 SCSS보다 빠르게 작성하고 쉽게 읽을 수 있음을 느낍니다. 들여쓰는 문법은 모두 같은 기능을 갖긴 하지 일부는 약간 다른 문법입니다. 이는 들여쓰기 문법 레퍼런스에 더 자세히 묘사되어 있습니다. 이 구문을 사용하는 파일의 확장자는 `.sass`입니다.

어느 한쪽 구문이든 다른 쪽 구문으로 작성된 파일을 가져올 수 있습니다. 아래와 같이 명령줄 도구 `sass-convert` 를 이용하여 파일들을 자동으로 한쪽에서 다른쪽으로 변환할 수 있습니다.

{% code-tabs %}
{% code-tabs-item title="Syntax.sh" %}
```text
# Convert Sass to SCSS
$ sass-convert style.sass style.scss

# Convert SCSS to Sass
$ sass-convert style.scss style.sass
```
{% endcode-tabs-item %}
{% endcode-tabs %}

이 명령은 CSS 파일을 생성하는 것이 아니라는걸 명심하세요. 그를 위해서는, 다른 곳에서 설명된 `sass` 명령을 사용하세요.  


