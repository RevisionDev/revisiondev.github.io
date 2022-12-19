---
layout: page
cover: assets/images/report/mac.jpg
title: MAC 주소란 무엇인가요? 
date: 2022-10-19 09:00:00 +0900
categories: report
author: Revision
main: true
report: true
summary: MAC 주소를 변조해 추적을 피해봅니다. 
---

<head>
 <style> .pic:hover {
   color: forestgreen;}
 a.pic:hover {
   color: forestgreen;
 text-decoration-line: none;} 
 a.pic {
   color: forestgreen;
 text-decoration-line: none;} 
 </style>
<center><br>
<img src="/assets/images/report/mac.jpg"> 
<br><br>
<h5 style="line-height:1.5;">MAC 주소를 변조해 추적을 피해봅니다.</h5> </center>

</head>

<br>

-  <h5 style="line-height:1.5;" >
사용자의 PC나 스마트폰 등에 설치된 프로그램, 어플리케이션 등은 사용자의 MAC 주소를 추적하거나 기록할 수 있습니다.</h5>
  MAC 주소란 무엇인지 그리고 어떻게 추적을 피할 수 있는지 알아봅니다.  
<br>
- <h5 style="line-height:1.5;" >MAC 주소란 무엇인가요?</h5>
  PC의 랜카드나 스마트폰, 태블릿, 스마트 워치 등의 와이파이 모듈에 할당된 기기의 ID입니다. 12자리의 알파벳과 숫자로 이루어져 있습니다.  
<br>
- <h5 style="line-height:1.5;" >PC와 스마트폰의 차이가 있나요?</h5>
  - 윈도우나 리눅스 등 OS의 경우, 별도의 설정이 없는 한, 기기 자체의 맥 주소를 그대로 사용합니다.<br>
단, 윈도우 10, 11의 Wi-Fi 무선 연결의 경우 **무작위로 생성된 맥 주소**를 사용할 수 있습니다.<br>
  - 최근 버전의 안드로이드(10 이상)와 iOS(8 이상)는 기기 자체의 맥 주소가 아닌 **무작위로 생성된 맥 주소**를 사용합니다.
<br><br><br>

- <h5 style="line-height:1.5;" >MAC 랜덤화 기능은 왜 사용하는 건가요?</h5>
  사용자의 식별과 추적을 피하기 위해서입니다. 공공 WiFi 등을 사용하는 경우에 사용자의 MAC 주소를 추적할 수 있어 사용자를 식별하거나 해킹 등의 공격을 할 수 있기 때문입니다.
<br><br>

- <h5 style="line-height:1.5;" >맥주소는 계속 바뀌는 건가요?</h5>
  - 기기 고유의 맥주소는 변경되지 않습니다.
  - 맥 랜덤화 기능으로 생성된 맥 주소의 경우, 별도의 설정이 없는 한, 처음으로 WiFi에 연결할 때 랜덤화된 주소를 사용하며, 이후 연결을 끊었다 다시 연결할 때는 자동으로 첫 연결과 동일한 주소를 계속 사용합니다. 이는 라우터의 IP 할당 등의 편의를 위한 것입니다.<br>
예를 들어 라우터의 관리자는 접속 기기의 MAC 주소를 확인하여 내부 IP를 할당하고, 허가된 사용자만 WiFi 사용을 허가하며 허가되지 않은 기기는 인터넷을 사용하지 못하게 설정할 수 있습니다.<br><br><br>

- <h5 style="line-height:1.5;" >내 MAC 주소는 누가 기록하고 보관하나요?</h5>
  - 스마트폰이나 셀룰러 모델의 태블릿, 스마트 워치 등의 통신사는 통신사 공공 WiFi의 제공을 위해 기기의 고유 MAC 주소를 수집하여 보관하고 있습니다. 
  - 기기 제조사 역시 자신들이 생산한 기기의 MAC 주소를 보관하고 있습니다만, 구체적으로 누가 사용하는지까지는 식별할 수 없습니다. 단 삼성, 애플 등의 계정에 가입한 경우나 제조사 어플에서는 기기의 실제 고유 MAC 주소를 수집할 수 있기 때문에 누가 MAC 주소의 사용자인지 식별할 수 있습니다. 또한 기기의 종류와 공급 통신사 및 국가 등의 사항 역시 충분히 알 수 있습니다.
  - 설치된 프로그램이나 어플리케이션에서도 MAC 주소의 수집이 가능합니다. 단, MAC 랜덤화 기능이 켜져있을 시에는 랜덤화된 MAC 주소만을 수집할 수 있으며 기기의 고유 MAC 주소는 수집할 수 없습니다.<br><br><br>
  
- <h5 style="line-height:1.5;" >웹 사이트의 운영자 등도 내 MAC 주소를 알 수 있나요?</h5>
  - 웹 사이트에서 MAC 주소나 IMEI 등의 정보를 수집하는 것은 불가능합니다.
  - 인터넷 서비스 제공자나 통신사의 경우 공유기와 사용기기의 MAC 주소를 수집할 수 있습니다.
  - 단, 웹사이트의 어플, 프로그램 등을 설치한 경우에는 수집이 가능합니다.<br><br><br>

- <h5 style="line-height:1.5;" >IMEI는 무엇인가요?</h5>
  IMEI는 스마트폰이나 태블릿 등의 고유 식별번호로 15자리의 숫자로 이루어져 있습니다. <br>통신사의 전화나 데이터 서비스가 이용 가능한 모든 기기마다 부여되어 있으며, 기기 제조사와 통신사가 수집 · 보관하고 있습니다. <br>
  IMEI와는 별개로 시리얼번호, 일련번호 등의 기기 제조사가 붙인 번호도 존재하며 이 번호 역시 기기 제조사와 통신사가 수집 · 보관하고 있습니다. <br>
  최근 버전의 안드로이드 및 iOS에서는 IMEI 및 일련번호 등은 어플(제조사 어플 제외)에서 수집할 수 없습니다.
<br><br>

- <h4 style="line-height:1.5;" >MAC 주소나 IMEI 등 기기정보를 노출해도 되나요?</h4>
  <img src="/assets/images/report/no.jpg"> <br>
  - **절대로 안됩니다.** 
  - 공공 WiFi 등 보안이 취약한 라우터에 접속할 때 특정된 타겟으로 인식하고 해킹 등 공격을 할 수 있습니다.
  - 또는 사이버 범죄를 저지르며 타인의 MAC 주소를 고의로 시스템에 남겨 누명을 씌우거나 수사에 혼선을 줄 수도 있습니다. 
  - 반대로 MAC 주소의 변조가 쉽기 때문에, 만약 범죄의 누명을 쓴 경우 도용당한 것이라고 주장할 수는 있으나, 현실적으로 12자리의 ID를 정확히 동일하게 맞추기는 불가능에 가까우며, 노출이 되기 힘든 구조라는 점을 알아둬야 합니다.<br>
단, 라우터의 관리자나 MAC 주소를 수집한 자가 MAC 주소를 도용하는 것이 불가능한 것은 아니기 때문에 공공 WiFi 등에 접속할 때는 반드시 MAC 랜덤화 기능을 사용하거나 수동으로 임의의 주소로 변경할 것을 권장합니다.    
<br><br>

- <h5 style="line-height:1.5;" >공공 WiFi를 사용하면 안되나요?</h5>
  - 일반적으로는 사용해도 되나 **유의할 필요는 있습니다.**<br> 가게 등에서 제공하는 것이 아니며 정체를 알 수 없는 WiFi, 비밀번호가 설정되어 있지 않은 WiFi나 핫스팟, 통신사나 가게 등에서 제공하는 것처럼 위장한 WiFi 등은 사용하지 않는 것을 권장합니다.  
  - 스토커 등이 추적 중이거나 추적할 가능성이 높은 연예인 등 대상자나 개인정보노출에 민감한 경우에는 공공 WiFi를 사용하지 않도록 합니다.  
  - 중간자 공격 등을 피하기 위해 로그인 등은 피하거나, 데이터 기능을 사용해서 올바른 URL로 들어가 로그인 한 후 다시 WiFi를 연결하도록 합니다. 
<br><br><br><br>


- <h4 style="line-height:1.5;" >맥 주소를 변경하거나 무작위 맥 주소를 사용하는 법</h4>
  - 별도의 설정을 건들지 않았다면, 일반적으로 MAC 랜덤화 기능은 자동으로 켜져 있습니다.
  - 각 OS별로 알아봅니다.
 <br><br><br>

- <h5 style="line-height:1.5;" >윈도우</h5>
  - 유선 연결 방법 
  1. 윈도우 키를 누른 뒤 검색창에 장치 관리자 입력 후 실행합니다.<br><br>
  <img src="/assets/images/report/steamgames/1.jpg"> <br><br><br>
  2. 장치관리자 - 네트워크 어댑터에서 사용중인 랜카드 속성 - 고급 - 네트워크 주소에서 숫자와 영어를 조합하여 아무런 값 16자리를 입력합니다.
영어는 A부터 F까지만 사용하도록 합니다.<br><br>
  <img src="/assets/images/report/steamgames/2.jpg"> <br><br><br>
  3. 윈도우 키를 누른 뒤 검색창에 cmd 입력 후 실행합니다.<br>
[ ipconfig/all ] 입력하여 이더넷 물리적 주소가 바뀌었는지 확인합니다. 또는 [ getmac ]을 입력해도 됩니다.<br><br>
  <img src="/assets/images/report/steamgames/3.jpg"> 
<br><br>
  - 무선 연결 방법 
  1. 윈도우 키 - 설정 - 네트워크 & 인터넷 - Wi-Fi에서<br>
임의 하드웨어 주소 사용 선택<br><br><br>

- <h5 style="line-height:1.5;" >리눅스</h5>
  1. 터미널에서 <code style="font-weight:normal">sudo macchanger -r (이더넷 이름)</code> 입력<br>
인터넷 이름은 **ifconfig**로 확인. 예시 : <code style="font-weight:normal">sudo macchanger -r eth0(wlan)</code> 등<br>
**macchanger** 존재하지 않을 시 <code style="font-weight:normal">sudo apt(yum) install macchanger</code> 입력하여 설치
<br><br><br>

- <h5 style="line-height:1.5;" >안드로이드</h5>
  1. 설정 - 연결- Wi-Fi - 연결된 와이파이 옆 톱니바퀴 - 더보기에서<br>
MAC 주소 유형 : 랜덤 MAC 설정<br><br>
  <img src="/assets/images/report/steamgames/s1.jpg"> <br><br>
  <img src="/assets/images/report/steamgames/s2.jpg"> <br><br>
  <img src="/assets/images/report/steamgames/s2.5.jpg"> <br><br>
  <img src="/assets/images/report/steamgames/s3.jpg"> <br><br>
  <img src="/assets/images/report/steamgames/s4.jpg"> <br><br>
  - 안드로이드의 개발자모드를 통한 더 강화된 랜덤 MAC 기능에 대해서는 다음 <a href="/report/2022/09/12/report-steam-censored.html" style="font-weight:bold; color:forestgreen;" class="pic" target="_blank">보고서</a>를 참고하십시오.
<br><br><br>

- <h5 style="line-height:1.5;" >iOS</h5>
  1. 설정 - Wi-Fi - 연결된 와이파이 옆 느낌표에서<br>
비공개 Wi-Fi 주소 사용 설정<br><br>
  <img src="/assets/images/report/steamgames/im1.png"> <br><br>
  <img src="/assets/images/report/steamgames/im2.png"> 
<br><br> <br><br>

- <h5 style="line-height:1.5;" >앱이 MAC 주소를 수집하는 지 어떻게 알 수 있나요?</h5>
  - 해당 어플의 앱스토어, 플레이스토어 등에서 밑으로 스크롤하여 데이터 보안에서 세부 내용을 확인할 수 있습니다.<br>
**기기 ID**를 수집한다고 기재되어 있을 시, MAC 주소를 수집해 가는 것입니다.
  - 해당하는 기업의 홈페이지에서 **개인정보처리방침**을 확인해도 MAC 주소 수집 여부, 보관 기관, 파기 방법등을 알 수 있습니다. <br>
대부분 홈페이지의 맨 아래 메뉴 부분에서 개인정보처리방침을 확인할 수 있습니다.<br>
대개 이용자의 인터넷 등 로그기록, 접속지 추적자료는 3~6개월, 그 외의 통신사실 확인 자료는 12개월동안 보관합니다.
<br><br><br>

- <h5 style="line-height:1.5;" >웹 사이트나 게임 등 운영사에서 MAC 주소로 차단을 하기도 하나요?</h5>

  - 게임 등 운영사에서 제재를 당한 후에 IP를 변경하여도 제재가 풀리지 않는다면 보관중인 MAC 주소를 이용했을 가능성이 높습니다.<br>
  - 웹 사이트는 MAC 주소를 수집할 수 없습니다.(웹 사이트의 어플, 프로그램 등을 이용한 경우 제외)<br>
  웹 사이트의 경우, 제재를 당한 후에 IP를 변경하여도 제재가 풀리지 않는다면, MAC 주소보다는 OS나 브라우저의 핑거프린팅 등의 정보를 이용했을 가능성이 높습니다.
<br><br><br>

- <h5 style="line-height:1.5;" >제재 중인 유저나 범죄자들이 악용할 수도 있지 않나요?</h5>

  - MAC 주소 변조 기능은 스마트 기기의 보급 확대로 인해 악성 추적 및 공격 행위가 급속도로 늘어났고, 최근 몇년간 개인정보보호 의식이 높아짐에 따라 MS 윈도우, 구글 안드로이드, 애플 iOS, macOS 등에서도 제공하는 자체 기능입니다.
  - 현재 **대한민국은 인터넷 검열 및 차단국가**로 인터넷 사이트는 물론 스팀 등 외산 게임까지 차단하는 등 자유민주주의국가가 아닌 중공국가라고 봐도 무방할 정도로, 도를 지나친 행태만을 이어가고 있습니다.<br>
리비전은 **국민의 자유와 권리 보호를 모토로 하는 사회적 기업으로서 국민의 권리 증진**에 항상 앞장서겠습니다.
  - 스팀 등 차단 우회 방법, DNS, VPN, Tor 등의 정보가 필요하다면 리비전의 다른 <a href="/report/" style="font-weight:bold; color:forestgreen;" class="pic" target="_blank">보안 보고서</a>들을 참고하십시오. 
  - 차단이 없으면 저항도 없을 것이며, 차단이 있기에 저항이 존재하는 것입니다. 
 <br><br><br><br><br>

<h5 style="line-height:1.7;"> 저작권 안내</h5>

   - 해당 게시물은 리비전의 유료저작물로 정기 구독 간행물 서비스를 통해 제공되는 컨텐츠입니다. 커뮤니티, 블로그 등으로 자유롭게 퍼갈 수 있으나 반드시 출처와 URL 주소를 남겨야 합니다. <br> <span style="word-break:break-all">
예시: 출처(리비전 홈페이지, https://revision.kr/report/2022/10/19/mac-address) </span>
   - 영리적 이용은 할 수 없습니다. 언론사 및 그 계열사의 경우 본 게시물을 신문, 방송, 인터넷신문, 웹사이트, 어플, 동영상 사이트, SNS 등에 보도하고자 할시 반드시 이메일을 통해 사전 허가를 받아야 하며, 사전 허가 없이 보도하는 것은 민·형사상 모든 책임과 손해의 모든 종류에 대해 무한한 책임을 지겠다는 것을 의미합니다.
   - 유튜브 같은 영상사이트의 경우, 해당영상광고중지 기능을 설정해 광고 재생을 중지해야 합니다. 더 많은 사람들 모두가 쉽게 보기 위해서입니다. 단, 본인이 수익창출을 하지 않으며, 해당 영상사이트에서 자체적인 광고를 재생하는 것은 무관합니다. 
   - 블로그 등 웹사이트의 경우, 애드센스 등의 광고를 해당 포스트 내에서 제거해야 합니다. 단, 해당 포스트의 광고만을 제거하는 것이 부득이하게 어렵거나 불가능할 경우, 그와 같은 이유를 포스트에 같이 명기함으로써 게시할 수 있습니다.
<br><br><br>


<h4 style="line-height:1.7; text-align:center;">리비전은 고객의 보안과 프라이버시 보호를 위해 언제나 최선을 다합니다.<br>
 고객의 보안이 최우선입니다. 리비전과 함께하십시오. </h4><br>

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
'https://revision6.tistory.com/m/10/comments';}
else {window.open('about:blank').location.href =
'https://https://revision6.tistory.com/10#comment13949363';} }

    </script>




</body>
</html>
