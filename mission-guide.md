## 코드 리뷰 요청 방법

### 미션 사전 세팅

---

#### 1. [바톤 홈페이지](https://baton-review.com)에 로그인한 후 이벤트 페이지로 이동합니다.
   ![](./review-step1-images/select_mission.png)

---

</br>


#### 2. 미션 시작 버튼을 클릭하면 해당 레포지토리에 본인 깃허브 아이디로 된 브랜치가 생성됩니다. 미션 시작 버튼을 눌렀음에도 본인의 브랜치가 생성되지 않았다면 문의주시면 감사하겠습니다.
   ![](./review-step1-images/my_team_btn.png)

---

</br>

#### 3. 미션 레포지토리에서 자신의 계정으로 fork 합니다.
   <img width="1265" alt="스크린샷 2023-09-12 오후 4 02 08" src="https://github.com/baton-mission/docs/assets/140675388/bb735334-e30f-4617-b9bc-7f0e7f1f9532">
   
   </br>
   <hr>
   </br>
   
   <img width="759" alt="스크린샷 2023-09-12 오후 4 06 00" src="https://github.com/baton-mission/docs/assets/140675388/82db7a65-29cf-40cb-bd78-fda40561e72d">

---

</br>

#### 4. fork가 완료되었다면 아래와 같이 본인의 레포지토리에 미션 저장소가 생성됩니다.

  <img width="1273" alt="스크린샷 2023-09-12 오후 4 11 20" src="https://github.com/baton-mission/docs/assets/140675388/54587104-f185-4a80-bc89-e21a5a89a8c6">


> baton-mission 저장소에 코드를 추가할 권한이 없기 때문에 구현한 코드를 추가할 수 없습니다. 그렇기 때문에 fork를 이용해 본인의 저장소로 복사를 진행했습니다.

---

</br>

#### 5. fork한 저장소를 자신의 컴퓨터로 clone 합니다.

  <img width="945" alt="스크린샷 2023-09-12 오후 4 12 53" src="https://github.com/baton-mission/docs/assets/140675388/c48ba271-b5ba-4e9b-9e28-142d908c8e8a">
  </br>
  
  5-1. `https://github.com/{본인 계정}/{레포지토리 이름}.git` 형태로 클립보드에 복사됩니다.
  5-2. 명령어를 통해 자신의 컴퓨터로 레포지토리를 클론합니다.
  ```bash
  git clone https://github.com/{본인 계정}/java-boss-monsters.git
  ```
  5-3. 클론된 디렉토리로 이동합니다.
  ```bash
  cd {디렉토리 명}
  ```

  아래는 명령어 실행 결과입니다.
  <hr>
  </br>
  
  <img width="644" alt="스크린샷 2023-09-12 오후 4 19 25" src="https://github.com/baton-mission/docs/assets/140675388/1d07cb42-5825-4c74-b28e-625d38125c33">

---

### 미션 진행중

---

#### 6. 기능 구현 시에 커밋 및 푸시

  6-1. 기능 구현을 완료하면 구현한 내용을 stage에 올립니다.
  ```bash
  git add {파일 명}
  // 수정된 전체 파일을 올리고 싶은 경우에는 git add .
  ```

  6-2. 커밋 메시지를 남깁니다.
  ```bash
  git commit -m "{커밋 메시지}"
  ```

  6-3. 푸시합니다.
  ```bash
  git push
  ```

  아래는 예시 실행 결과입니다.
  
  <img width="644" alt="스크린샷 2023-09-12 오후 4 38 21" src="https://github.com/baton-mission/docs/assets/140675388/80af35e4-8607-4c14-9a25-eaedfee148f0">

---

### 미션 진행후

---

</br>

#### 7. PR 생성하기

  푸시가 완료되었다면 본인 계정 레포지토리에 아래와 같이 작성한 코드가 반영됩니다.
  <img width="919" alt="스크린샷 2023-09-12 오후 4 41 05" src="https://github.com/baton-mission/docs/assets/140675388/f90f429c-97c2-4006-aaa3-b4eea7d3d699">

  7-1. pull request 버튼을 클릭합니다.
  <img width="1557" alt="스크린샷 2023-09-12 오후 4 42 31" src="https://github.com/baton-mission/docs/assets/140675388/6417704d-b781-422d-94ec-81b10356e71f">

  7-2. new pull request 버튼을 클릭합니다.
  <img width="1513" alt="스크린샷 2023-09-12 오후 4 43 55" src="https://github.com/baton-mission/docs/assets/140675388/726dc8fc-670b-41f8-82f6-d1013ea4d756">

  7-3. 본인이 작업한 브랜치에서 baton-mission의 본인 아이디 브랜치로 pull request를 요청할 수 있도록 pull request 방향 설정을 합니다.
  ![image](https://github.com/baton-mission/docs/assets/140675388/0877daf4-72d5-42c3-a995-6ead33ff7613)

  7-4. create pull request 버튼을 클릭합니다.
  <img width="1247" alt="스크린샷 2023-09-12 오후 4 52 38" src="https://github.com/baton-mission/docs/assets/140675388/dcc55d03-9fd4-43ef-8273-ea080fdb9d8c">

  7-5. pull request 제목과 메시지를 작성한 후에 create pull request 버튼을 클릭합니다.
  <img width="1101" alt="스크린샷 2023-09-12 오후 4 58 41" src="https://github.com/baton-mission/docs/assets/140675388/33e019de-9ad9-4f45-903e-42f2d30e73af">

  7-6. 바톤 미션 저장소에 pull request가 생성된 것을 확인할 수 있습니다.
  <img width="1037" alt="스크린샷 2023-09-12 오후 5 00 41" src="https://github.com/baton-mission/docs/assets/140675388/3adf2e78-3bbe-4ac4-bb36-f551ede0c942">

  </br>

---

#### 8. 바톤 홈페이지에 리뷰 요청 글 올리기

  8-1. 바톤 홈페이지에 로그인 한 후에 글을 작성합니다.
  고민하신 부분이나 구현 내용을 자세히 적어주시면 리뷰어가 리뷰하는데 있어 도움이 많이 됩니다:)
  
  ![이미지 2023  9  12  오후 5 06](https://github.com/baton-mission/docs/assets/140675388/a446c55a-efe7-42ce-b4a8-6a26f5582225)

  조금 기다리시면 리뷰어께서 리뷰 제안을 할 예정입니다. 마이 페이지에서 제안온 리뷰를 확인해보시고 원하는 리뷰어를 선택하시고 리뷰 받으시면 됩니다!

