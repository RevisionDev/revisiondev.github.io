---
layout: page
cover: assets/images/report/cookies.png
title: 자바스크립트·쿠키 차단 가이드
date: 2022-09-17 09:00:00 +0900
categories: report
author: Revision
main: true
report: true
summary: 자바스크립트·쿠키 차단 가이드
---

<head>
 <style> .pic:hover {
   color: forestgreen;} 
a.pic:hover {
   color: forestgreen; 
   text-decoration-line: none;}
a.pic: {
   color: forestgreen; 
   text-decoration-line: none;}
</style>
<center><br>
<img src="/assets/images/report/cookies.png"> 
<br><br>
<h5 style="line-height:1.5;">자바스크립트와 쿠키 차단 방법을 알아봅니다. </h5> </center>

</head>

<br>
<h5 style="line-height:1.5;">자바스크립트란 무엇인가요? </h5>

자바스크립트는 웹을 구성하는 프로그래밍 언어입니다.
    
<h5 style="line-height:1.7;">자바스크립트는 나쁜 요소인가요?</h5>

자바스크립트 자체는 스크립트 언어일 뿐이며 웹을 구성하기 위해서는 반드시 사용이 필요합니다.<br>
단, 최대한 사용을 자제하거나 기능 구현을 포기하고 html만으로 웹사이트를 구성할 수는 있으며 토어브라우저를 위해 만들어진 단순한 사이트들이 그에 해당합니다. 그러나 고의로 만들어진 악성 자바스크립트는 다음과 같은 사용자의 정보를 수집할 수도 있습니다. <br>
<code> 사용자의 언어, 지역, IP 주소, 접속 경로, OS, 브라우저, 모니터 해상도, 기기 정보 등 </code> 
- 자바스크립트로 유출되는 정보를 확인해보고싶다면 <a href="https://browserleaks.com" style="color:forestgreen; font-weight:bold; text-decoration-line: none;" target="_blank" class="pic">browserleaks.com</a>에서 테스트 해볼 수 있습니다.
<br>
<h5 style="line-height:1.5;">쿠키란 무엇인가요? </h5>

쿠키란 웹사이트에 의해 사용자의 PC와 브라우저에 저장되는 정보입니다.
    
<h5 style="line-height:1.7;">쿠키는 나쁜 요소인가요?</h5>

쿠키는 사용자의 로그인 정보 유지와 편의기능 등을 위해 사용됩니다.<br>
단, 악성 쿠키는 사용자의 의사와 관계없이 광고나 마케팅을 위해 사용되거나 개인정보를 유출하거나 기타 공격에 사용되기도 합니다.
<br>
<h5 style="line-height:1.5;">자바스크립트와 쿠키를 차단해야하나요? </h5>

반드시 차단할 필요는 없습니다. 모든 기능을 차단할 시 웹사이트의 정상적 이용이 불가능하기 때문입니다. 신뢰할 수 있는 사이트라면 차단하지 않아도 무관합니다. 또는 사이트 별로 설정을 달리하거나 원하는 차단 정도를 설정할 수 있습니다. 개인정보에 민감하거나 추적을 피하기 위해서라면 자바스크립트와 쿠키를 차단해야 합니다. 
<br><br>

<h4 style="line-height:1.7;">다음은 자바스크립트·쿠키 차단방법입니다.</h4>

- <h5 style="line-height:1.7;">크롬 또는 크로뮴 기반 브라우저(삼성 인터넷, MS 엣지 제외) </h5>
 설정 - 고급 - 사이트 설정에서 쿠키와 자바스크립트의 설정을 변경할 수 있습니다.<br>
 모두 차단 또는 단계별로 설정하십시오. PC용 브라우저도 UI만 다를뿐 동일합니다.<br><br>
 <img src="/assets/images/report/nonscript/s1.png"><br><br>
 <img src="/assets/images/report/nonscript/s2.png">
<br><br>
- <h5 style="line-height:1.7;">마이크로 소프트 엣지</h5>
 설정 - 쿠키 및 사이트 권한에서 쿠키와 자바스크립트의 설정을 변경할 수 있습니다.<br>
 모두 차단 또는 단계별로 설정하십시오. <br><br>
 <img src="/assets/images/report/nonscript/ed.png">
<br><br>
- <h5 style="line-height:1.7;">삼성 인터넷(안드로이드)</h5>
 설정 - 사이트 및 다운로드 - 사이트 권한에서 쿠키와 자바스크립트의 설정을 변경할 수 있습니다.<br>
 모두 차단 또는 단계별로 설정하십시오. <br><br>
 <img src="/assets/images/report/nonscript/sa1.png"><br><br>
 <img src="/assets/images/report/nonscript/sa2.png"><br><br>
 <img src="/assets/images/report/nonscript/sa3.png"><br><br>

- <h5 style="line-height:1.7;">파이어 폭스</h5>
 설정 - 개인 정보 및 보안 - 향상된 추적 방지 기능에서 쿠키와 자바스크립트의 설정을 변경할 수 있습니다.<br>
 엄격 또는 사용자 지정에서 원하는 수준으로 설정하십시오. 모바일 브라우저도 UI만 다를뿐 동일합니다.<br><br>
 <img src="/assets/images/report/nonscript/ff1.jpg"><br>

   PC용 브라우저에서는 고급 기능을 사용해 자바스크립트를 완전히 차단할 수 있습니다. <br>
   주소창에 [ about:config ]를 입력합니다. 위험을 감수하고 계속 진행 버튼을 누릅니다.<br>
   [ javascript ]를 검색 후 [ javascript.enabled ] 의 기능을 끕니다. 개발자가 아니라면 다른 기능은 건들지 마십시오.<br><br>
   <img src="/assets/images/report/nonscript/ff1.5.jpg"><br><br>
   <img src="/assets/images/report/nonscript/ff2.jpg"><br><br>

- <h5 style="line-height:1.7;">토어 브라우저</h5>
 토어 브라우저는 기본적으로 어느 정도 쿠키와 추적 스크립트를 차단합니다.<br>
 더 안전한 차단을 원할 시에는 설정 - Privacy & Security(보안 설정)에서 Safest(제일 안전)을 선택합니다.<br><br>
 <img src="/assets/images/report/nonscript/t.png"><br><br>

- <h5 style="line-height:1.7;">사파리</h5>
 설정 - 개인 정보 보호 및 보안에서 쿠키 설정을 변경할 수 있습니다.<br><br>
 <img src="/assets/images/report/nonscript/ic.jpg"><br><br>
 설정 - 고급에서 자바스크립트의 설정을 변경할 수 있습니다. <br><br>
 <img src="/assets/images/report/nonscript/is1.jpg"><br><br>
 <img src="/assets/images/report/nonscript/is2.jpg">
<br><br><br><br>
<h5 style="line-height:1.7;"> 저작권 안내</h5>

   - 해당 게시물은 리비전의 유료저작물로 정기 구독 간행물 서비스를 통해 제공되는 컨텐츠입니다. 커뮤니티, 블로그 등으로 자유롭게 퍼갈 수 있으나 반드시 출처와 URL 주소를 남겨야 합니다. <br> <span style="word-break:break-all">
예시: 출처(리비전 홈페이지, https://revision.kr/report/2022/09/17/blocking-javaScript-cookie) </span>
   - 영리적 이용은 할 수 없습니다. 언론사 및 그 계열사의 경우 본 게시물을 신문, 방송, 인터넷신문, 웹사이트, 어플, 동영상 사이트, SNS 등에 보도하고자 할시 반드시 이메일을 통해 사전 허가를 받아야 하며, 사전 허가 없이 보도하는 것은 민·형사상 모든 책임과 손해의 모든 종류에 대해 무한한 책임을 지겠다는 것을 의미합니다.
   - 유튜브 같은 영상사이트의 경우, 해당영상광고중지 기능을 설정해 광고 재생을 중지해야 합니다. 더 많은 사람들 모두가 쉽게 보기 위해서입니다. 단, 본인이 수익창출을 하지 않으며, 해당 영상사이트에서 자체적인 광고를 재생하는 것은 무관합니다. 
   - 블로그 등 웹사이트의 경우, 애드센스 등의 광고를 해당 포스트 내에서 제거해야 합니다. 단, 해당 포스트의 광고만을 제거하는 것이 부득이하게 어렵거나 불가능할 경우, 그와 같은 이유를 포스트에 같이 명기함으로써 게시할 수 있습니다.
<br><br><br>


<h4 style="line-height:1.7; text-align:center;">리비전은 고객의 정보보호를 위해 언제나 최선을 다합니다.
<br> 리비전의 <a href="/privacypolicy" style="color:forestgreen; font-weight:normal; text-decoration-line: none;" target="_blank" class="pic">개인정보처리방침</a>을 확인하십시오. <br>
 정보보호와 프라이버시 보호가 최우선입니다. 리비전과 함께하십시오. </h4><br>

<h2 style="line-height:1.7; font-family:goodtime;text-align:center;"> Security Renovation <br> with Revision</h2>




<html>
<body>
<br>
<hr/>
 <input type="button" style="background-color:transparent; border:none; cursor:pointer;
 font-size:16px; font-weight:bold; font-family:NanumSquareRoundB; " class="pic"
  value="댓글보기" onclick="mb();" >
<br>
    <script src="https://utteranc.es/client.js"
            repo="Revisionsix/reply"
            issue-term="pathname"
            theme="github-dark"
            crossorigin="anonymous"
            async>
    </script>

    <script>
 function mb(){ 
var ratio = window.devicePixelRatio;
if(ratio>1){window.open('about:blank').location.href =
'https://revision6.tistory.com/m/4/comments';}
else {window.open('about:blank').location.href =
'https://revision6.tistory.com/4#comment13905825';} }

    </script>




</body>
</html>
