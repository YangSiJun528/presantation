---
marp: true
#theme: gaia
#class: invert
#paginate: true
#header: Awesome Header!
#footer: Copyright 2023. **Archmond** All right reserved.
---

 
# Hello Marp!
 
## Markdown Presentation ecosystem
 
마크다운으로 프레젠테이션을 만들어보자!
 
web: https://marp.app/
 
via: https://www.youtube.com/watch?v=Q2PCO0mKEaU
 
---
 
# Create another slide
 
다음 슬라이드를 추가하려면 ```---```를 넣으면 OK입니다!
 
# Marp ships with two another themes
 
Marp에는 기본적으로 uncover, gaia라는 테마가 제공됩니다.
 
```theme: uncover or gaia```
 
---
 
# Class directive we can get dark mode
 
```class: invert```으로 다크모드로 전환하는 것이 가능합니다.
 
# add page numbers to presentation
 
```paginate: true```으로 프레젠테이션에 페이지 번호를 넣을 수 있습니다.
 
# a footer or header to all slides
 
```footer```와```header```로 푸터와 헤더를 넣을 수 있습니다.
 
---
 
# add a background image to slide
 
![bg right](https://assets.st-note.com/production/uploads/images/51957246/rectangle_large_type_2_a4346e0af597ee8b694e86a56f6238c7.jpg?width=2000&height=2000&fit=bounds&quality=85)
 
```![bg](URL)```으로 배경을 넣는다.
 
```![bg right](URL)```으로 오른쪽으로 배치할 수 있다.
 
---
 
# size images
 
![w:400](https://pbs.twimg.com/media/FQntwfNagAAfV0m?format=jpg&name=900x900)
![w:250](https://pbs.twimg.com/media/FQntwfNagAAfV0m?format=jpg&name=900x900)
 
```![w:500](URL)```와 같이 이미지의 크기를 지정할 수 있다.
 
---
 
# Marp support Code Highlighting
 
\```Code```
 
```java
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!"); 
    }
}
```
 
---
 
# Related link
 
## community themes
 
https://github.com/topics/marp-themes
 
## Marpit: Markdown slide deck framework
 
https://marpit.marp.app/markdown
 
---
 
# Export
 
- PDF Slide
- HTML Slide
- PowerPoint Slide
 
※ PNG/JPG Image(First slide only)