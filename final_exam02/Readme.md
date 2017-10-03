## 종합 예제2

<br/>

#### 화면
![final_exam02_1](https://github.com/mdy0501/HTML5/tree/master/final_exam02/01.PNG)
![final_exam02_2](https://github.com/mdy0501/HTML5/tree/master/final_exam02/02.PNG)

<br/>

#### 소스 코드
```HTML5
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>HTML5 Basic Page</title>
  </head>
  <body>
    <!-- 전체를 감싸는 태그-->
    <div id="page-wrapper">
      <!-- 헤더 -->
      <header id="main-header">
        <hgroup>
          <h1 class="master-title">HTML5 Example Preview</h1>
          <h2 class="master-description">한빛아카데미</h2>
        </hgroup>
      </header>

      <!-- 내비게이션 -->
      <nav id="main-navigation">
        <div class="pull-left">
          <ul class="outer-menu">
            <li class="outer-menu-item">
              <span class="menu-title">HTML5</span>
              <ul class="inner-menu">
                <li class="inner-menu-item"><a href="#">데이터1-1</a></li>
                <li class="inner-menu-item"><a href="#">데이터1-2</a></li>
              </ul>
            </li>

            <li class="outer-menu-item">
              <span class="menu-title">CSS3</span>
              <ul class="inner-menu">
                <li class="inner-menu-item"><a href="#">데이터2-1</a></li>
                <li class="inner-menu-item"><a href="#">데이터2-2</a></li>
                <li class="inner-menu-item"><a href="#">데이터2-3</a></li>
              </ul>
            </li>

            <li class="outer-menu-item">
              <span class="menu-title">JavaScript</span>
              <ul class="inner-menu">
                <li class="inner-menu-item"><a href="#">데이터3-1</a></li>
                <li class="inner-menu-item"><a href="#">데이터3-2</a></li>
                <li class="inner-menu-item"><a href="#">데이터3-3</a></li>
                <li class="inner-menu-item"><a href="#">데이터3-4</a></li>
                <li class="inner-menu-item"><a href="#">데이터3-5</a></li>
                <li class="inner-menu-item"><a href="#">데이터3-6</a></li>
                <li class="inner-menu-item"><a href="#">데이터3-7</a></li>
                <li class="inner-menu-item"><a href="#">데이터3-8</a></li>
              </ul>
            </li>
          </ul>
        </div>

        <div class="pull-right">
          <div class="search-bar">
            <form>
              <input type="text" class="input-search" />
              <input type="submit" class="input-search-submit" value="검색" />
            </form>
          </div>
        </div>
      </nav>

      <!-- 본문 -->
      <div id="content">
        <!-- 본문 좌측 영역 -->
        <section id="main-section">
          <article>
            <div class="article-header">
              <h1 class="article-title">HTML5 개요와 활용</h1>
              <p class="article-date">2017년 10월 3일</p>
            </div>
            <div class="article-body">
              <img src="http://placehold.it/430x280" />
              <br/>
              <br/>
              <p>Lorem ipsum dolor sit amet.</p>
              <br/>
              <p>Proin ut fringilla sapien..</p>
            </div>
          </article>

          <article>
            <div class="article-header">
              <h1 class="article-title">HTML5 응용과 실습</h1>
              <p class="article-date">2017년 10월 7일</p>
            </div>
            <div class="article-body">
              <img src="http://placehold.it/430x280" />
              <br/>
              <br/>
              <p>Lorem ipsum dolor sit amet.</p>
              <br/>
              <p>Proin ut fringilla sapien.</p>
            </div>
          </article>
        </section>

        <!-- 본문 우측 영역 -->
        <aside id="main-aside">
          <div class="aside-list">
            <h3>카테고리</h3>
            <ul>
              <li><a href="#">데이터1-1</a></li>
              <li><a href="#">데이터1-2</a></li>
              <li><a href="#">데이터1-3</a></li>
              <li><a href="#">데이터1-4</a></li>
              <li><a href="#">데이터1-5</a></li>
            </ul>
          </div>
          <div class="aside-list">
            <h3>최근 글</h3>
            <ul>
              <li><a href="#">데이터2-1</a></li>
              <li><a href="#">데이터2-2</a></li>
              <li><a href="#">데이터2-3</a></li>
              <li><a href="#">데이터2-4</a></li>
            </ul>
          </div>
        </aside>

      </div>

      <!-- 푸터 -->
      <footer id="main-footer">
        <a href="#">Created By MDY</a>
      </footer>
    </div>
  </body>
</html>
```
