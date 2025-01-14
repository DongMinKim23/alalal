# Readme_Together

## 설치 방법 및 실행 순서

- git bash를 사용하여 저장소에 있는 프로젝트 폴더를 가져옵니다.

  ```bash
  > git clone https://lab.ssafy.com/dongmin/together.git
  ```

- 프로젝트 폴더을 열고, pjt_trip 폴더를 Atom 또는 VS code로 실행시킵니다.

- 실행한 에디터의 터미널에서 노드 패키지 모듈을 설치합니다.

  ```bash
  > npm install // 설치가 완료되면, 프로젝트를 로컬 환경에서 실행시킵니다.
  > npm run dev
  ```

- 프로그램이 실행되면, 우측 상단에 있는 Login 버튼을 눌러 회원 가입을 진행합니다.

  - Email : 이메일은 주소 양식을 맞춰주어야합니다. ( ex : giljune@naver.com )
  - Phone_number : '-'을 제외한 번호만 작성하시면 됩니다.
  - 성별 : 남성 / 여성을 기재해주시면 됩니다.
  - 이메일 중복 확인 버튼을 누르면, 계정이 중복되어있는지를 확인할 수 있습니다.

- Tour page 
  - 회원가입이 완료되고, 해당 계정으로 로그인을 하여
  - Tour page에서 여행하고 싶은 테마를 선택합니다.
  - 여행지들을 리스트로 볼 수 있으며, 해당 여행지에 대한 디테일 페이지로 들어갈 수 있습니다.
- DetailPage
  - 좋아요와 일정을 담을 수 있는 기능이 존재
  - 평점을 선택할 수 있으며, 후기도 남길 수 있습니다.
  - 일정을 담은 것들은 Schedule 페이지에서 일정을 계획 할 수 있습니다
- Traveling
  - 현재 위치를 가져와서 지도에 보여줍니다.
  - 현재 지역의 테마 별 여행지 추천 기능
  - 현재 미세먼지에 따라 여행지를 추천
  - 현재 위치의 근방 1km 이내의 병원의 위치를 가르쳐줍니다.