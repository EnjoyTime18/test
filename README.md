# Spring Boot project: 미니 익명 게시판
⚡ Spring Boot + Spring Data JPA를 이용한 프로젝트입니다. <br>
⚡ 익명성을 보장해 주는 작은 게시판 웹 서비스입니다. <br>
⚡ 누구나 어떠한 조건과 제한 없이 게시글과 댓글을 작성, 수정, 삭제 가능하며 여러 조건을 통한 게시글과 관련된 검색 기능을 지원합니다.
<br/><br/>

## :hourglass: 개발 기간
09/7/23 ~ 09/19/23
<br/><br/>

## :hammer_and_wrench: 기술 스택 
<p>
 <img src="https://img.shields.io/badge/spring boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=green">
 <img src="https://img.shields.io/badge/spring data jpa-59666C?style=for-the-badge&logo=hibernate&logoColor=white">
 <img src="https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white">
 <img src="https://img.shields.io/badge/java-0F2B77?style=for-the-badge&logo=openjdk&logoColor=white"> 
 <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">  
  
 <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
 <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
 <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
 <img src="https://img.shields.io/badge/Thymeleaf-%23005C0F.svg?style=for-the-badge&logo=Thymeleaf&logoColor=white">
 <img src="https://img.shields.io/badge/Axios-5A29E4.svg?style=for-the-badge&logo=Axios&logoColor=white)">
 <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
 <img src="https://img.shields.io/badge/bootstrap-9933FF?style=for-the-badge&logo=bootstrap&logoColor=white">
 
 <img src="https://img.shields.io/badge/spring tool suite 4-6DB33F?style=for-the-badge&logo=spring&logoColor=green">
 <img src="https://img.shields.io/badge/Visual Studio Code-00A6CC?style=for-the-badge&logo=visualstudiocode&logoColor=blue">
 <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
 <img src="https://img.shields.io/badge/sourcetree-0052CC?style=for-the-badge&logo=sourcetree&logoColor=white">
</p>

<br/><br/>

## :runner: 참여 인원
Name|GitHub Address|
|------|---|
|:teddy_bear:조성민|https://github.com/EnjoyTime18|

<br/><br/>

## :books: ERD
![ERD](https://github.com/EnjoyTime18/test/assets/122413012/6027fef4-59d3-448a-b2c8-e3bea0b99ad6)
<br/><br/>

# :gear: 주요 기능 
* [:clipboard: 게시글 CRUD – 조회, 글 상세보기 및 페이징 기능](#clipboard-게시글_조회_상세보기_페이징)<br>
* [:clipboard: 게시글 CRUD – 등록, 수정, 삭제 기능](#clipboard-게시글_등록_수정_삭제)
* [:mag_right: 게시글 CRUD – 복합 검색 기능](#clipboard-게시글_복합_검색)
* [:clipboard: 댓글 CRUD – 조회, 등록 기능](#clipboard-댓글_조회_등록)
* [:clipboard: 댓글 CRUD – 수정, 삭제 기능](#clipboard-댓글_수정_삭제)
* [:face_with_head_bandage: Trouble Shooting](#face_with_head_bandage-trouble-shooting)
<br><br>

## :clipboard: 게시글 CRUD – 조회, 글 상세보기 및 페이징 기능 <a name="clipboard-게시글_조회_상세보기_페이징"></a>
![검색_지도](https://user-images.githubusercontent.com/87034370/229581639-96dc01db-0aef-4355-9f1f-355e09aa2c56.gif)<br><br>
* 메인 페이지의 이미지 카테고리(지역)을 조건으로 해당 지역의 호텔을 마커로 표시해줍니다.<br><br>
* 마커를 클릭하면 호텔 정보 창이 출력되며, 바로가기를 클릭 시 상세페이지로 이동합니다.<br><br>
[:gear: 주요 기능](#gear-주요-기능)
<br><br>

## :clipboard: 게시글 CRUD – 등록, 수정, 삭제 기능 <a name="clipboard-게시글_등록_수정_삭제"></a>
![검색](https://user-images.githubusercontent.com/122413012/230009947-5d286592-7ab8-497e-9b5e-38a24ec94c4e.gif)
<br/><br/>
![재검색](https://user-images.githubusercontent.com/122413012/230009921-7103cf78-3ed3-4d06-9fcf-72ee616f0e8d.gif)
<br>

* 메인 페이지의 호텔 검색 조건(지역, 체크인/체크아웃, 인원(객실)수, 등급)을 설정하고 검색 버튼을 누르면 검색조건에 해당하는 호텔 정보 리스트가 출력됩니다. 
* 호텔 이름 클릭 시 해당 호텔 세부정보 페이지로 이동합니다. 
* 호텔 예약 재검색 기능으로 메인페이지에서 되돌아가 다시 호텔을 검색하지 않고 이미 호텔이 검색된 목록 페이지에서 동기 방식으로 재검색하여 검색조건에 맞는 호텔목록을 보여줍니다.
<br><br>
[:gear: 주요 기능](#gear-주요-기능)
<br/><br/>

## :mag_right: 게시글 CRUD – 복합 검색 기능 <a name="clipboard-게시글_복합_검색"></a>
<img src="https://user-images.githubusercontent.com/116073413/230076109-5a7a08f2-5836-470c-8ae6-90245915a893.gif" width="100%" height="90%" title="px(픽셀) 크기 설정" >
<br>

* 로그인은 Spring Security에서 관리됩니다.
* 로그인은 두가지의 방법이 있으며 첫번째는 일반적인 Spring Security 폼 인증, 두번째는 OAuth2 의 소셜 로그인 인증입니다.
* 최초로 소셜 로그인을 한 사용자는 ‘소셜 등급‘ 의 권한을 부여 받으며 추후에 이메일 인증을 해야 사이트의 모든 기능을 사용할 수 있습니다. 
<br><br>
[:gear: 주요 기능](#gear-주요-기능)
<br/><br/>

## :clipboard: 댓글 CRUD – 조회, 등록 기능 <a name="clipboard-댓글_조회_등록"></a>
![관리자_차트](https://user-images.githubusercontent.com/87034370/229581658-75e2c170-8834-4263-a08f-bc448d60ec01.gif)<br><br>
* 원형 차트는 지역별 총 매출, 열 차트는 가장 많이 찜을 받은 선호도 상위 호텔 5개를 조회 할 수 있습니다.
<br><br>
[:gear: 주요 기능](#gear-주요-기능)
<br><br>

## :clipboard: 댓글 CRUD – 수정, 삭제 기능 <a name="clipboard-댓글_수정_삭제"></a>
<img src="https://user-images.githubusercontent.com/116073413/230073771-e58cd554-d425-4c7a-9e72-68cdf53855d1.gif" width="100%" height="90%" title="px(픽셀) 크기 설정" >

<br>

* 회원가입시 ‘아이디’, ‘비밀번호‘, ‘이름‘, ‘이메일’ 이 요구됩니다.
* ‘아이디‘ 는 ‘중복확인’기능을 사용하여 사용 가능한 아이디 인지 확인합니다. 
* ‘비밀번호‘는 한번 더 입력하여 오타나 잘못된 입력을 사전에 방지하고, 입력한 비밀번호가 일치하지 않으면 경고 문구가 출력됩니다.
* 위의 모든 조건을 만족하기 전까지는 ‘회원가입‘ 버튼은 비활성화 상태로 유지됩니다. 
<img src="https://user-images.githubusercontent.com/116073413/230077557-ec1694e3-2d97-44c3-afbe-f22643e5a32d.jpg">

* 회원가입시 입력한 비밀번호는 암호화 되어 저장되기 때문에 비밀번호 유출 등의 보안 문제를 방지할 수 있습니다. 
<br><br>
[:gear: 주요 기능](#gear-주요-기능)
<br/><br/>

## :face_with_head_bandage: Trouble Shooting
:page_facing_up: 메인 페이지<br><br>
> :rotating_light: 메인 페이지에서 스크롤 시 크롬 웹 브라우저 관리자 도구에서 네트워크 탭에 이미지 로고 파일이 스크롤 시 마다 이미지가 로드 되는 문제 발생 -> 스크롤 시 렉 유발 발                   생
> * 메인 페이지에서 스크롤 시 자바 스크립트 단에 스크롤 이벤트 함수가 발생되어 적용되어 있는데 그 함수에 스크롤 시 마다 로고 이미지 파일이 로드 되는 코드를 발견하여 해당 코드 삭제     하여 문제 해결

 <br><br>:world_map: 검색방법 : 지도<br><br>
 
> :rotating_light:이미지 카테고리에 onclick속성을 이용해 해당 지역 위도와 경도값을 map.html로 넘겨 주는 스크립트 함수를 구현해 위도와 경도 값을 포함하는url을 구성  → url encoding 문제에 봉착.
> * 기존 위도와 경도 값을 사용하는 코드 폐기, Thymeleaf 반복문으로 프로젝트 내부의 지역 사진을 가져오고 있는 코드를 수정하는 방향 선정.
> * -> 사진을 가져오는 반복문에서, 지역의 pk를 파라미터로 받는 새로운 컨트롤러를 호출해 해당 지역의 데이터와 해당 지역을 조건으로 호텔과 호텔 이미지의 데이터를 담고 있는 DTO 두가지를 model로 전달한다.

> :rotating_light: Script 내부에서 Thymeleaf 표현식을 사용 못함.
> * Thymeleaf는 서버 측에서 HTML 템플릿을 생성하는 데 사용.
> * 주석(/**/)을 사용하거나, script를 감싸는 태그에 **th:attr** 속성을 사용해 할당된 변수를 사용한다.

> :rotating_light:마커를 찍기위해 호텔의 위경도 값을 가져와야하며, 해당 지역을 클릭하면 그 지역에 관련된 호텔만 불러와야한다. 
> * 지역을 조건으로 해당 호텔만 추출하도록 쿼리 작성.
> * 호텔 entity에 @Embedded로 선언된 필드에있는 위경도 값을 사용한다.
> * 가져온 hotel객체에서 대부분의 정보를 사용할 수 있다.

> :rotating_light:마커 클릭으로 출력되는 인포윈도우에 담을 정보 중에, 사진은 첫번째 사진 한장만 나오게 변경해야한다. 
> * 조건에 맞는 쿼리문을 작성.
> * -> 해당 지역의 호텔 사진 중 첫번째 사진은 마지막이름이 1번이다. like연산자를 통해 첫번째 이미지만 불러온다.


<br><br>:mag_right: 검색방법 : 조건 검색<br><br>
>  :dart: 메인페이지 조건 검색시 해당 조건에 맞게 입력값 반환을 원하는 상황  →  null pointer Exception, Syntax Error발생
> *  @param어노테이션의 이름과 변수명이 일치하지 않는 경우 오류 발생. 동일하게 수정 후 해결 <br>
> *  Syntax Error 이 부분도 쿼리문에서 사용되는 테이블 및 칼럼 이름 확인하고 데이터베이스에서 정의된 이름과 동일하게 수정 후 해결<br>


 <br><br>:necktie: 관리자 : 통계차트<br><br>
 > :rotating_light: 원형 차트 : 넘어 오는 데이터는 의도한 대로 넘어 왔지만, script에서 값이 없어 차트가 보이지 않는 상황. (List<Object[]>형식으로 넘어가며, script는 JSON.parse() 로  변환.)
 > * JSON 문자열을 파싱해 주고 있었지만, 직렬화하지 않았음.
 > * 내부 객체&데이터를 외부의 시스템에서도 사용할 수 있게 바이트 형태로 직렬화&역직렬화.

 > :rotating_light: 열 차트 : 행차트를 구현하려 했지만, 템플릿과 맞지 않는 문제가 발생.
 > * 열 차트 구현으로 노선 변경. but 호텔 이름이 길어 겹치는 문제발생.
 > * 호텔이름 겹치는 문제는 크기를 키우고, 잘리는 문제는 상위 5로 조정.

 <br><br>:pinching_hand: URL에 허용되지 않는 값 오류처리
 > * url 데이터 누락 -> 파라미터 없음 & 파라미터에 값 없음.
 > * 날짜 임의 작성 -> 잘못된 날짜 데이터.
 > * 위의 두가지의 경우의 수를 잡아, alert 메세지와 바로 뒤로가는 동작을하는 페이지로 이동.
 > * 잘못된 컨트롤러 요청 -> error/404
 
 <br><br>:moneybag: 결제<br><br>
 > :rotating_light: 호텔 상세보기 페이지단에 방 리스트 탭 및 결제 페이지에서 1박 가격 값이 천(1000) 단위마다 콤마가 적용 안되서 숫자 데이터 가독성 문제점 발생 
 > * Thymeleaf 문법 함수 #numbers.formatInteger 적용해서 문제점 해결

<br><br>
[:gear: 주요 기능](#gear-주요-기능)
