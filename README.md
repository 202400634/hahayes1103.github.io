<html>
    <head><metacharset="utf-8">
    <title>셀렉터만들기</title>
    <style>
        h3 { 
text-align : right; /* 오른쪽 정렬 */
 }
    h3, li { /* 태그이름셀렉터*/
    color : brown;
    }
    div>div>strong{/* 자식셀렉터*/
    background : yellow;
    }
    ulstrong { /* 자손셀렉터*/
    color : dodgerblue;
    }
    .warning { /* class 셀렉터*/
    color : red;
    }
    body.main{ /* class 셀렉터*/
    background : pink; 
   }
    #list { /* id 셀렉터*/
    background : mistyrose;
    }
    #list span{ /* 자손셀렉터*/
    color : forestgreen;
    }
    h3:first-letter{ /* 가상클래스셀렉터*/
    color : red;
    } 
   li:hover{/* 가상클래스셀렉터*/
    background : yellowgreen;
    }
</style></head>
 <body class="main">
 <h4>무엇이든 물어보세요! 해결사 척척 페이지</h4>
 <h3>2020400634 이예린</h3>
 <hr>
 <div> 
<div>도움이 필요한 일에<strong>필요봇 페이지</strong>를 찾아주세요!><</div>
 <ul id="list">
 <li><span>청소 부문</span></li>
 <li><strong>프로그램 부문</strong></li>
 <li>만들기 부문</li>
 </ul>
 </div>
 </body>
 </html>
