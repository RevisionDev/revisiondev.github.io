---
layout: page
cover: assets/images/report/steam.jpg
title: 정부차단으로 인한 스팀지역락 우회
date: 2022-09-12 08:00:00 +0000
categories: report
author: Revision
main: true
report: true
summary: 정부차단으로 인한 스팀지역락 우회
---


<head>
 <style> .pic:hover {
   color: forestgreen;} </style>
<center>
<img src="/assets/images/report/steam.jpg"> 
<br><br>
<h4> 정부의 국민 검열과 차단에 대해 반대합니다. </h4> </center>

</head>

 현재 대한민국 정부는 국내의 모든 민간 기업인 ISP의 DNS 서버를 감시하며 국민의 인터넷 접속을 차단하고 있으며, 더 나아가 국제 암호화 표준 통신규격인 HTTPS마저 감청하기 위해 SNI 차단까지 감행했습니다.
 전세계 국가 중 이러한 검열과 차단을 하는 국가는 중국과 러시아, 북한, 중동의 강경한 이슬람 국가들뿐으로 사회주의독재국가, 독재왕정국가들과 대한민국이 어깨를 나란히 하고 서있는 것입니다.
 자유민주주의에 반하는 이러한 검열과 차단행위로 인해 대한민국은 자유서방세계 국가들로부터 외교적 불이익과 문화적 조롱을 당하고 있으며 인접국가와 분쟁 발생시에도 대한민국의 편에 서는 나라는 단 한 곳도 존재하지 않습니다.
    
 대한민국 정부의 강요로 전세계적인 미국의 기업 스팀은 자국의 문화컨텐츠들을 한국 거주자들이 이용할 수 없게 조치했습니다.

 이에 리비전은 지역락이 걸린 컨텐츠의 우회이용법에 대해 공유하고자 합니다.

 현재 VPN을 통한 IP 우회같은 단순한 방법으로는 계정 생성이 막힌 상황이니 다음 절차를 따르십시오. 
        
- 1단계 : 구글 등 이메일 계정 새로 만들기. 구글 가입에는 휴대폰 인증등이 필요할 수 있습니다. 

- 2단계 : 각 OS별로 설명합니다.
 
 - **Window** : 먼저 맥주소를 위조해야 합니다.
       
    1. 장치 관리자를 실행합니다.
       <img src="/assets/images/report/steamgames/1.jpg">
       
    2. 사용하는 랜카드의 속성에 들어갑니다.
       고급 - 네트워크 주소를 선택하고 값 16자리를 새롭게 입력
       예시 : A0B0C0D1E1F1 / 알파벳은 F까지만 사용하십시오.
       <img src="/assets/images/report/steamgames/2.jpg">  


    3. 윈도우 키를 눌러 나오는 검색창에 cmd를 입력해 실행한 뒤 [ ipconfig /all ] 을 입력하여 맥주소가 변경되었는지 확인합니다.
        물리적 주소가 맥주소입니다. 변경되지 않았을 시에는 재부팅 후 다시 1단계부터 실행합니다. 
        <img src="/assets/images/report/steamgames/3.jpg">
 
<br><br>
 - **Linux** : sudo macchanger -r [이더넷 이름] 명령어로 맥주소를 위조합니다.
    macchanger가 존재하지 않을시 apt, yum 등 사용하는 리눅스의 종류에 따라 설치하면 됩니다. 
    [이더넷 이름]은 ifconfig 명령어를 통해 확인할 수 있습니다.
    예시 : sudo macchanger -r eth0
<br><br>
 - **Android** : 설정 - 밑으로 내려서 휴대전화 정보 - 소프트웨어 정보에 들어갑니다.
    빌드번호를 7번 터치하여 개발자 옵션을 활성화 시킵니다.
    다시 처음 설정 화면으로 나가 화면을 내리면 개발자 옵션이 생긴 것을 확인할 수 있습니다.
        <img src="/assets/images/report/steamgames/m1.jpg">
    개발자 옵션에서 강화된 wi-fi mac 무작위 옵션을 켜고 와이파이 연결을 해제한 후 다시 연결합니다.
    연결된 와이파이 설정화면으로 들어가 맨 아래로 내려보면 바뀐 맥주소를 확인할 수 있습니다.

  **중요! 개발자 설정을 사용한 후에는 반드시 다시 비활성화하십시오. 특히 개발자가 아닌 이상 USB 디버깅 등 내부 설정을 건드릴시 보안 취약점이 생깁니다**
<br><br>

 - **IOS** : 설정 - 와이파이 - 네트워크 옆에 있는 i 버튼 - 개인 주소 또는 비공개 주소 사용
    이미 사용중일때는 와이파이 연결 해제 후 다시 연결하여 맥주소가 변경됐는지 확인
     


      
 - 3단계 : VPN을 실행합니다. VPN의 종류는 상관없으나 신뢰할 수 있는 VPN을 추천합니다. 미국 지역 설정시 달러 결제 / 유럽 지역 설정시 유로화 결제가 이뤄집니다.

    <br><br>





<html>
<body>
    <hr />
    <input type="button" style="background-color:transparent; border:none; cursor:pointer;
 font-size:16px; font-weight:bold; font-family:NanumSquareRoundB; " class="pic"
           value="댓글보기" onclick="mb();">
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
        'https://revision6.tistory.com/m/2/comments';}
        else {window.open('about:blank').location.href =
        'https://revision6.tistory.com/2#comment13895772';} }

    </script>




</body>
</html>