---
layout: default
avatar: true
permalink: /
---
## 🚀 Hello World
Hello world 프로그램은 "Hello, world!"를 화면에 출력하는 컴퓨터 프로그램이다. 이 프로그램은 프로그래밍 언어를 연습하는 데에 많이 쓰이고, 많은 프로그래밍 언어 서적에서 가장 처음 만들어보는 기본 예제로 나온다.

Hello world 프로그램은 프로그래밍 언어로 할 수 있는 간단한 것 중 하나이다. 그러나, GUI를 사용할 때를 비롯하여, 어떤 경우에는 코드가 대단히 복잡해질 수 있다. 또 다른 경우에는 프로그램 자체는 간단하지만 CLI 셸에서 입력해야 하는 파라미터가 많아 복잡한 경우도 있다. 또 임베디드 시스템에서는 글자들이 한정된 한두 줄의 LCD에 표시될 것이다. 더욱 심한 경우에는 글자를 표시할 수 없어 "Hello world!" 대신에 간단하게 LED 점 등을 할 수도 있다.

You can use this page to showcase your work, portfolio/project, your Latest post {% for post in site.posts limit: 1 %}<a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>{% endfor %} or another stuff that you love to share to the world.

---

## 🅿️ Edit This Page
You’ll find this page in your `_pages` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.
