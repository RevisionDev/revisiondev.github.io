---
layout: page
cover: assets/images/report/steam.jpg
title: 정부에 차단된 스팀지역락 우회법
date: 2022-09-13 00:00:00 +0900
categories: report
author: Revision
main: true
report: true
summary: 정부에 차단된 스팀지역락 우회법
---

<head>
 <style> .pic:hover {
   color: forestgreen;} 
a.pic:hover {
   color: forestgreen; text-decoration-line: none;}
a.pic: {
   color: forestgreen; text-decoration-line: none;}
</style>
<center>
<img src="/assets/images/report/steam.jpg"> 
<br><br>
<h4 style="line-height:1.5;">정부의 국민 검열과 차단에 대해 반대합니다. </h4> </center>

</head>

<br>
 <h5 style="line-height:1.5;">&nbsp;&nbsp;현재 대한민국 정부는 국내의 모든 민간 기업인 ISP의 DNS 서버를 감시하며 국민의 인터넷 접속을 차단하고 있으며, 더 나아가 국제 암호화 표준 통신규격인 HTTPS마저 감청하기 위해 SNI 차단까지 감행했습니다.<br><br>
 &nbsp;&nbsp;전세계 국가 중 이러한 검열과 차단을 하는 국가는 중국과 러시아, 북한, 중동의 강경한 이슬람 국가들뿐으로 사회주의독재국가, 독재왕정국가들과 대한민국이 어깨를 나란히 하고 서있는 것입니다.<br><br>
 &nbsp;&nbsp;자유민주주의에 반하는 이러한 검열과 차단행위로 인해 대한민국은 자유서방세계 국가들로부터 외교적 불이익과 문화적 조롱을 당하고 있으며 인접국가와 분쟁 발생시에도 대한민국의 편에 서는 나라는 단 한 곳도 존재하지 않습니다.</h5><br>
    
<h5 style="line-height:1.7;"> &nbsp;&nbsp;최근 스팀은 대한민국 정부의 강요로 인해 자국의 문화컨텐츠들을 한국 거주자들이 이용할 수 없게 조치했습니다.<br>
 이에 리비전은 지역락이 걸린 컨텐츠의 우회이용법에 대해 공유하고자 합니다.</h5>

 <h5 style="line-height:1.7;">&nbsp;&nbsp;현재 VPN을 통한 IP 우회같은 단순한 방법으로는 계정 생성이 막힌 상황이니 다음 절차를 따르십시오. </h5>
 <br>
자유롭게 퍼가되, 반드시 글 끝에 있는 저작권 조항을 지켜주세요.
<br>
- <h4 style="line-height:1.7;">1단계 : 구글 등 이메일 계정 새로 만들어놓기.  구글 가입에는 휴대폰 인증등이 필요할 수 있습니다. </h4>

- <h4 style="line-height:1.7;">2단계 : 각 OS별로 설명합니다.</h4>

  - **Window** : 먼저 할 것은 맥주소 변조입니다.
       
    1. 장치 관리자를 실행합니다. <br>

       <img src="/assets/images/report/steamgames/1.jpg">
       <br>
    2. 사용하는 랜카드의 속성에 들어갑니다.<br><br>
       고급 - 네트워크 주소를 선택하고 값 16자리를 새롭게 입력합니다.<br>
       예시 : A0B0C0D1E1F1 / 알파벳은 A~F만 사용하십시오.<br>
       <img src="/assets/images/report/steamgames/2.jpg">  
<br>

    3. 윈도우 키를 눌러 나오는 검색창에 cmd를 입력해 실행한 뒤 [ ipconfig /all ] 을 입력하여 맥주소가 변경되었는지 확인합니다.<br>
        물리적 주소가 맥주소입니다. 변경되지 않았을 시에는 재부팅 후 다시 1단계부터 실행합니다. <br>

        <img src="/assets/images/report/steamgames/3.jpg">

 <br>
  - **Linux** : sudo macchanger -r [이더넷 이름] 명령어로 맥주소를 위조합니다.<br>
    macchanger가 존재하지 않을시 apt, yum, snap 등 사용하는 리눅스의 종류에 따라 설치하십시오.<br> 예시 : sudo apt install macchanger <br>
    [이더넷 이름]은 ifconfig 명령어를 통해 확인할 수 있습니다.<br>
    예시 : sudo macchanger -r eth0
<br><br>
  - **Android** : 설정 - 밑으로 쭉 내려서 휴대전화 정보 - 소프트웨어 정보에 들어갑니다.<br>
    빌드번호를 7번 터치하여 개발자 옵션을 활성화 시킵니다.<br>
    다시 처음 설정 화면으로 가 화면을 내리면 개발자 옵션이 생긴 것을 확인할 수 있습니다.<br>

    <img src="/assets/images/report/steamgames/m1.jpg"><br><br>
    개발자 옵션에서 강화된 wi-fi mac 무작위 옵션을 켜고 와이파이 연결을 해제한 후 다시 연결합니다.<br>

    <img src="/assets/images/report/steamgames/m2.jpg"><br>

    연결된 와이파이 옆 톱니바퀴를 눌러 설정화면으로 들어가십시오. 가장 아래로 내려 맥주소가 변경되었는지 확인하십시오.<br>

    **중요!  개발자 설정을 사용한 후에는 반드시 다시 비활성화하십시오. 특히 개발자가 아닌 이상 USB 디버깅 등 내부 설정을 건드릴시 보안 취약점이 생깁니다.**
<br><br>

  - **iOS** : 설정 - 와이파이 - 네트워크 옆에 있는 i 버튼 - 비공개 Wi-Fi 주소를 사용하십시오.<br>
    이미 사용중일때는 사용을 잠시 중지하거나 와이파이 완전 제거 후 재연결하여 맥주소가 변경됐는지 확인하십시오.<br><br>
     <img src="/assets/images/report/steamgames/im1.png"><br><br>
<img src="/assets/images/report/steamgames/im2.png"><br><br>

      
- <h4 style="line-height:1.7;">3단계 : VPN을 실행합니다. VPN의 종류는 상관없으나 신뢰할 수 있는 VPN을 추천합니다. </h4>
미국 지역 설정시 달러 결제 / 유럽 지역 설정시 유로화 결제가 이뤄집니다. <br>

    <img src="/assets/images/report/steamgames/4.jpg"><br>
    <br>
   PC, Mac 등은 VPN 프로그램을. 안드로이드, iOS는 스토어에서 VPN 어플을 다운로드 받으면 됩니다. <br>   DNS 우회 어플이 아닌 VPN 어플을 사용하십시오.
 예시 : 프로톤, 노드, 뮬바드, 익스프레스, 서프샤크 VPN 등 <br>    미국 또는 유럽 등으로 지역을 변경한 뒤, 네이버, 구글, 덕덕고 등에 '내 아이피, my ip' 등을 검색해 IP가 변경되었는지 확인하십시오. 
<br><br>

- <h4 style="line-height:1.7;">4단계 : 이제 스팀을 실행하거나 스팀 홈페이지에서 회원가입을 진행합니다. <br></h4>
1단계에서 만들어둔 이메일 계정으로 가입합니다. VPN을 사용할시 리캡챠 인증이 오래 걸릴 수 있습니다. <br>인내심을 가지고 완성하면 되며, 무한 반복·오류 등 발생시 다른 VPN, 다른 PC 등에서 시도하는 것을 권장합니다.<br><br>

- <h3 style="line-height:1.7;">5단계 : 매우 중요한 단계입니다! 먼저 실행하지마십시오!</h3>
  <h4 style="line-height:1.7;">이메일 인증이 필요합니다. 이 때는 반드시 변조한 맥주소와 IP로 메일에 로그인해서 인증받아야 합니다. 지역이 다를 시 인증에 실패하며 1단계부터 다시 처음부터 해야합니다.</h4>

  즉, 맥주소와 IP를 변조하고 스팀의 회원가입을 진행한 기기에서 그대로 메일에 로그인해 인증메일을 확인하면 되며, 절대로 다른 기기나 맥주소, IP주소 등이 다른 기기에서 인증메일을 확인하면 안됩니다.
<br><br>
- <h3 style="line-height:1.7;">6단계 : 축하합니다! 외국 지역으로 설정된 계정 생성에 성공했습니다!<br></h3>
이제 당신은 달러화 또는 유로화로 표시된 상점을 볼 수 있으며, 지역락이 걸린 모든 컨텐츠가 표시될 것입니다. <br>구매는 신용·체크카드(비자, 마스터카드) 등으로 현지통화 결제하거나 페이팔 등 다른 수단을 이용하면 됩니다.
<br><br>
<img src="/assets/images/report/steamgames/d1.jpg"><br>
<img src="/assets/images/report/steamgames/d2.jpg"><br>

   만약 상점에 원하는 컨텐츠가 표시되지 않는다면 아래 설정을 확인해 모두 체크하십시오.<br><br>
   <img src="/assets/images/report/steamgames/st.jpg"><br><br><br>


<h5 style="line-height:1.7;">부록 : 다음은 대한민국 정부 게임물관리위원회가 선정한 작품성 우수 게임물 목록입니다. 배열은 무작위이며 순위가 아닙니다.</h5>

  <h5 style="line-height:1.7;">    - Orc Massage <br>    - Incubus <br>    - Escape Dungeon 2 <br>   -  Hero's Journey <br>     - HoneySelect2Libido DX <br>    - Karryn's Prison <br>    - Koikatsu Party (VR포함) <br>    - Furry Love <br>    - Mirror <br>    - 헤레즈의 투기장 (1,2) <br><br> </h5>

<h5 style="line-height:1.7;"> 추신 : 지역락을 뚫는 원리는 무엇인가요? </h5>

   - 스팀은 사용자가 사용하는 기기의 IP와 Mac주소, 해상도, 주변기기, 부품 등 환경정보를 수집했고, 여기서 수집된 정보로 사용자를 국적별로 분류하여 타 지역 가입을 막는 것입니다.<br>
   - 스팀은 주기적으로 사용자들을 대상으로 기기 성능, 사용하는 부품 등의 조사를 해왔고 사용자들은 성실히 임해왔습니다.<br> 하지만 스팀은 사용자들의 헌신에 보답하기는 커녕 무분별한 정보의 수집과 지역락으로 돌려주었습니다.<br>
   - 스팀 같은 대기업의 정보 수집을 경계해야 하겠습니다.   
<br><br>
<h5 style="line-height:1.7;"> 저작권 안내</h5>

   - 해당 게시물은 리비전의 유료저작물로 정기 구독 간행물 서비스를 통해 제공되는 컨텐츠입니다. 커뮤니티, 블로그 등으로 자유롭게 퍼갈 수 있으나 반드시 출처와 URL 주소를 남겨야 합니다. <br> <span style="word-break:break-all">
예시: 출처(리비전 홈페이지, https://revision.kr/report/2022/09/12/report-steam-censored) </span>
   - 영리적 이용은 할 수 없습니다. 언론사 및 그 계열사의 경우 본 게시물을 신문, 방송, 인터넷신문, 웹사이트, 어플, 동영상 사이트, SNS 등에 보도하고자 할시 반드시 이메일을 통해 사전 허가를 받아야 하며, 사전 허가 없이 보도하는 것은 민·형사상 모든 책임과 손해의 모든 종류에 대해 무한한 책임을 지겠다는 것을 의미합니다.
   - 유튜브 같은 영상사이트의 경우, 해당영상광고중지 기능을 설정해 광고 재생을 중지해야 합니다. 더 많은 사람들 모두가 쉽게 보기 위해서입니다. 단, 본인이 수익창출을 하지 않으며, 해당 영상사이트에서 자체적인 광고를 재생하는 것은 무관합니다. 
   - 블로그 등 웹사이트의 경우, 애드센스 등의 광고를 해당 포스트 내에서 제거해야 합니다. 단, 해당 포스트의 광고만을 제거하는 것이 부득이하게 어렵거나 불가능할 경우, 그와 같은 이유를 포스트에 같이 명기함으로써 게시할 수 있습니다.
<br><br><br>


<h4 style="line-height:1.7; text-align:center;">리비전은 고객만족을 위해 언제나 최선을 다합니다.
<br> 방법이 없다고 주저하지 않으며, 반드시 해결합니다. <br>
 정보보호와 프라이버시 보호, 지금 리비전과 함께하십시오. </h4><br>

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
'https://revision6.tistory.com/m/3/comments';}
else {window.open('about:blank').location.href =
'https://revision6.tistory.com/3#comment13899771';} }

    </script>




</body>
</html>
