# 종합 예제1
- #### 기본 공간 분할
  - ##### `Header`, `Navigation`, `Section`, `Aside`, `Footer`

<br/>
<br/>

#### 소스 코드
```HTML5
<!DOCTYPE html>
<html>
  <head>
    <title>HTML5 Basic Page</title>
  </head>
  <body>
    <!-- 전체를 감싸는 태그-->
    <div id="page-wrapper">
      <!-- 헤더 -->
      <header id="main-header">      </header>

      <!-- 내비게이션 -->
      <nav id="main-navigation">      </nav>

      <!-- 본문 -->
      <div id="content">
        <!-- 본문 좌측 영역 -->
        <section id="main-section">        </section>
        <!-- 본문 우측 영역 -->
        <aside id="main-aside">        </aside>
      </div>

      <!-- 푸터 -->
      <footer id="main-footer">      </footer>
    </div>
  </body>
</html>
```
