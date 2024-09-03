## 1. 프로젝트 소개
#### 1.1. 개발배경 및 필요성
- 개발 배경
  > 양산시에 위치한 부산대학교 양산캠퍼스 학생들은 매일 즐거운 학교생활을 보내는 나머지 하루하루 금전난에 시달리고 있다. 식비와 생활비부터 동아리 회비와 수업교재 값 까지 학생들은 많은 비용을 지출하게 된다. 이러한 이유로 많은 학생들이 학기 중임에도 알바를 구하려 하는 추세를 보인다. 이때 학생들은 주로 알바 구직 어플을 사용한다. 이 과정에서 우리는 더 효율적인 알바 어플을 구현할 수 없는지에 대한 의문이 생겼다.

- 개발 필요성
  > 일반적인 알바 구직 어플은 알바의 종류와 시간대, 그리고 임금 정도의 정보만을 제공하고 있다. 하지만 학기 중에 알바를 구하는 대학생의 경우에는 수업 시간이나 동아리 활동 등 고려해야 할 점이 더 많다. 따라서 우리 팀은 이러한 번거로움을 해결하기 위해 기존의 알바 어플 구직 어플에서 나아가, 대학생 개개인의 학업 및 스케쥴을 고려한 맞춤 알바 매칭어플을 개발하고자 한다.

#### 1.2. 개발목표 및 주요 내용
- 개발목표
  > 대학생의 학업 시간표를 입력받아 이를 분석하여 구하고자 하는 알바의 시간대와 겹치지 않도록 확인하고, 알바 시급 또는 장소를 포함하여 알바를 추천해주는 알고리즘을 개발하고자 한다. 또한, 양산에서 알바를 구하고자 하는 사업자들의 협력을 통해 여러 알바 정보를 제공한다. 우리가 개발할 앱을 통해 부산대학교 양산캠퍼스에 재학중인 학생들이 알바를 더욱 간편하게 구하고, 학업과 알바의 균형을 맞추는데 도움을 주고자 하며, 지역사회의 경제 활성화에도 기여하는 것이 이 프로젝트의 최종적인 목표이다.

- 주요 내용
  > 먼저, 앱을 실행하면 ID와 PW를 입력하는 로그인창이 띄워지도록 한다. 이때, 계정등록이 안되어있다면, 회원가입하는 창도 만든다. 회원가입은 ID와 PW, 앱 내에서 사용할 닉네임을 작성하는 칸이 있고, 작성 후 본인 명의를 확인한다. 회원가입이 되면, 회원의 정보를 앱의 클라우드에 저장하고, 이후 로그인을 할 때마다 클라우드에서 회원의 정보와 일치하는지 확인하게 된다.
최초 로그인 이후, 생년월일, 성별, 학과, 학년 등을 작성하는 개인정보 작성란을 띄운다. 필수적으로 등록해야 하기에, 작성을 하지 않는다면 다음 화면으로 넘어가지 않는다. 작성을 완료했다면, 사용자의 개인정보도 앱의 클라우드에 저장된다.

  > 또한, 알바를 구인하고자 하는 사업자의 경우, 사업자 항목에 체크하고, 사업자 인증을 추가로 진행한다.
이제, 사용자의 학업 시간표를 등록하는 창을 띄운다. 학업 시간표의 경우, 월금까지 오전 9시부터 오후 5시까지의 빈 시간표에서 자신이 듣는 수업의 시간을 등록할 수 있다. 시간표 등록의 편의를 위해 앞에서 작성한 개인정보를 이용해 학과별, 학년별 전공기초나 필수교양들을 선택할 수 있도록 한다. 이외의 교양선택이나 일반선택과 같은 수업들은 1영역부터 8영역까지의 영역을 선택하여 그 안에서 자신이 듣는 수업을 선택할 수 있도록 한다. 이외에도 동아리와 같은 개개인의 매주 루틴을 작성하여 추가할 수 있도록 하여 시간표를 완성한다.

  > 사업자의 경우, 자신의 사업장, 시급, 기간, 요일, 모집 조건과 같은 알바 구인 정보를 작성할 수 있도록 한다. 이때 들어가야 할 모집 조건은 모집 마간 기한, 모집 인원, 성별, 연령, 학력, 우대 사항 등이 있다. 근무조건은 급여, 근무기간, 근무요일, 근무시간, 직종, 고용형태(알바나 계약직), 복리후생 등이 있다.

#### 1.3. 세부내용
- 시간표 시스템
  > 내용
- 로그인 시스템
  > 내용
- 검색 시스템
  > 내용
- 알바 추천 시스템
  > 내용

#### 1.4. 기존 서비스 대비 차별성
  - 대학생들에게 최적화된 구직 방법
    > 알x몬과 같은 기존의 알바 구직 어플과는 달리, 시간표 연동이라는 기능을 이용하여 시스템 상에서 자동으로 시간표 내의 수업시간을 제외한 알바들을 검색해준다.
    <details>
      <summary>이미지 보기</summary>
      <img src="[https://ibb.co/3R1yt9b](https://ifh.cc/g/qWwvlP.png)" alt = "설명">
    </details>
  -
  -

#### 1.5. 사회적가치 도입 계획
  - 대단한 사회적가치가 있다 .
    > 내용내용

## 2. 상세설계
#### 2.1. 시스템 구성도
  > 우리의 내용
#### 2.2. 사용 기술
  > 별로 한 게 없지만 사용한 기술 나열

## 3. 개발결과
#### 3.1. 전체시스템 흐름도
  > 준비한 그것을 넣을 것.
#### 3.2. 기능 설명
  > 없지만 친히 기능을 설명할 것.
#### 3.3. 기능명세서
  > 이건뭐야
#### 3.4. 디렉토리 구조
  > 그것 .

## 4. 설치 및 사용 방법
- 안드로이드는 apk 파일을 통해 설치, 실행

## 5. 소개 및 시연 영상

## 6. 팀 소개
  - 팀장 윤상현
    >
  - 개발 및 디자이너 조은서
    >
  - 개발 및 디자이너 박선영
    >
  - 개발 및 디자이너 구예미
    >
## 7. 해커톤 참여 후기
  - 윤상현 :
  - 조은서 :
  - 박선영 :
  - 구예미 :






