<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F52FF,100:3DDC84&height=190&section=header&text=Dongwon%20Shin&fontColor=ffffff&fontSize=46&fontAlignY=36&desc=Android%20Developer%20%C2%B7%20Kotlin%20%C2%B7%20Jetpack%20Compose&descAlignY=58&descSize=18&animation=fadeIn" />

<a href="https://edvedv.tistory.com"><img src="https://img.shields.io/badge/Blog-000000?style=flat-square&logo=Tistory&logoColor=white" /></a>
<a href="mailto:edvedv613@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=Gmail&logoColor=white" /></a>
<a href="https://github.com/edv-Shin?tab=repositories"><img src="https://img.shields.io/badge/Repositories-181717?style=flat-square&logo=GitHub&logoColor=white" /></a>
<img src="https://img.shields.io/badge/Seoul,%20Korea-4285F4?style=flat-square&logo=GoogleMaps&logoColor=white" />
<img src="https://komarev.com/ghpvc/?username=edv-Shin&style=flat-square&color=3DDC84&label=visitors" />

</div>

---

## 🚀 주요 경험 (Project Experience)

### **Project: [운다방](https://github.com/projects200/android) (운동 습관 · 파트너 매칭 서비스)**

<a href="https://play.google.com/store/apps/details?id=com.project200.undabang"><img src="https://img.shields.io/badge/Google%20Play-414141?style=flat-square&logo=GooglePlay&logoColor=white" /></a>

* **기간:** 2025.04 ~ 진행 중
* **한 줄 요약:** 운동 기록부터 타이머, 파트너 매칭, 피드까지 한 앱에서 이어지는 운동 습관 서비스
* **팀 구성:** 4명 (Android 1, Frontend 1, Backend 2)
* **주요 역할:** Android 앱 개발 전담
* **주요 성과:**
  * 초기부터 Presentation-Domain-Data 계층을 분리하고 기능 단위 멀티모듈로 설계, Gradle로 의존성 방향을 강제해 **비즈니스 로직 커버리지 80%** 확보 (전체 빌드 140초 / 증분 평균 3초)
  * Fragment 내 Compose 호스팅으로 **7개 기능 모듈 중 6개 · 21개 화면** 점진 전환, 공통 컴포넌트 9종을 디자인 시스템으로 추출
  * GitHub Actions로 PR 자동 테스트와 Firebase / Play Store 배포를 자동화해 **배포 30분 → 5분 이내**
  * 지도 뷰포트 30% 이동 임계값 기반 조건부 호출로 카메라 이벤트마다 발생하던 중복 API 요청 제거

### **Project: [나모](https://github.com/Namo-log/Android) (모임 일정 · 공유 일기 서비스)**

* **기간:** 2024.03 ~ 2025.04
* **한 줄 요약:** 그룹을 만들어 모임 일정을 추가하고 모임 공유 일기를 기록하는 서비스
* **팀 구성:** 9명 (Android 2, iOS 3, Backend 2, PM 1, Designer 1)
* **주요 역할:** Android 파트장, Android 개발
* **주요 성과:**
  * View와 Controller를 동시에 수행하던 Activity/Fragment에서 비즈니스 로직을 ViewModel로 분리하고 UI/Domain/Data 레이어를 설계해 **주요 화면 View 코드 평균 40% 감소**
  * 라이브러리로는 불가능했던 장기 일정 연속 바, 주 경계 분할, 겹침 정렬을 **Canvas 커스텀 캘린더**로 직접 구현하고 개인/모임 두 캘린더에 드로잉 로직 재사용
  * 중첩 콜백을 suspend 함수로 전환하고 Data Source 레이어로 대체해 에러 추적 경로를 하나로 통일

> 📁 더 많은 작업은 [Repositories](https://github.com/edv-Shin?tab=repositories)와 소속 조직에서 볼 수 있어요.

<br/>

## 🛠️ 보유 기술 (Skills)

<table>
<tr>
<td><b>Language</b></td>
<td>
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=Kotlin&logoColor=white" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=OpenJDK&logoColor=white" />
</td>
</tr>
<tr>
<td><b>UI</b></td>
<td>
<img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=JetpackCompose&logoColor=white" />
<img src="https://img.shields.io/badge/Material%203-757575?style=flat-square&logo=MaterialDesign&logoColor=white" />
<img src="https://img.shields.io/badge/XML-2C2C2C?style=flat-square" />
</td>
</tr>
<tr>
<td><b>Architecture</b></td>
<td>
<img src="https://img.shields.io/badge/Clean%20Architecture-2C2C2C?style=flat-square" />
<img src="https://img.shields.io/badge/MVVM-2C2C2C?style=flat-square" />
<img src="https://img.shields.io/badge/Multi--Module-2C2C2C?style=flat-square" />
</td>
</tr>
<tr>
<td><b>Async</b></td>
<td>
<img src="https://img.shields.io/badge/Coroutines-7F52FF?style=flat-square&logo=Kotlin&logoColor=white" />
<img src="https://img.shields.io/badge/Flow-7F52FF?style=flat-square&logo=Kotlin&logoColor=white" />
</td>
</tr>
<tr>
<td><b>Network</b></td>
<td>
<img src="https://img.shields.io/badge/Retrofit-48B983?style=flat-square&logo=Square&logoColor=white" />
<img src="https://img.shields.io/badge/OkHttp-3E4348?style=flat-square&logo=Square&logoColor=white" />
<img src="https://img.shields.io/badge/Moshi-2C2C2C?style=flat-square" />
<img src="https://img.shields.io/badge/WebSocket-2C2C2C?style=flat-square" />
</td>
</tr>
<tr>
<td><b>Local</b></td>
<td>
<img src="https://img.shields.io/badge/Room-003B57?style=flat-square&logo=SQLite&logoColor=white" />
<img src="https://img.shields.io/badge/DataStore-3DDC84?style=flat-square&logo=Android&logoColor=white" />
<img src="https://img.shields.io/badge/WorkManager-3DDC84?style=flat-square&logo=Android&logoColor=white" />
</td>
</tr>
<tr>
<td><b>DI</b></td>
<td>
<img src="https://img.shields.io/badge/Hilt-2C2C2C?style=flat-square" />
</td>
</tr>
<tr>
<td><b>Test</b></td>
<td>
<img src="https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=JUnit5&logoColor=white" />
<img src="https://img.shields.io/badge/MockK-2C2C2C?style=flat-square" />
<img src="https://img.shields.io/badge/Turbine-2C2C2C?style=flat-square" />
<img src="https://img.shields.io/badge/Robolectric-2C2C2C?style=flat-square" />
</td>
</tr>
<tr>
<td><b>CI/CD</b></td>
<td>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=GitHubActions&logoColor=white" />
<img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=Firebase&logoColor=white" />
<img src="https://img.shields.io/badge/ktlint-2C2C2C?style=flat-square" />
<img src="https://img.shields.io/badge/JaCoCo-2C2C2C?style=flat-square" />
</td>
</tr>
<tr>
<td><b>Collaboration</b></td>
<td>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white" />
<img src="https://img.shields.io/badge/Slack-4A154B?style=flat-square" />
<img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white" />
<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white" />
</td>
</tr>
</table>

<br/>

## ✍️ Writing

<!-- BLOG-POST-LIST:START -->
- [매칭 지도 구현기 &lpar;2&rpar; 지도 API 호출 최소화](https://edvedv.tistory.com/66)
- [매칭 지도 구현기 &lpar;1&rpar; 마커 클러스터링](https://edvedv.tistory.com/65)
- [Polling에서 WebSocket으로의 전환기](https://edvedv.tistory.com/64)
- [에러 처리를 하나로 통합하기](https://edvedv.tistory.com/63)
- [나모의 코루틴 사용](https://edvedv.tistory.com/62)
<!-- BLOG-POST-LIST:END -->

<br/>

## 📊 GitHub Stats

<div align="center">

<table>
<tr>
<td valign="top">
<img src="https://github-readme-stats.vercel.app/api?username=edv-Shin&show_icons=true&count_private=true&hide_border=true&disable_animations=true&theme=react&bg_color=0D1117&title_color=3DDC84&icon_color=7F52FF&text_color=C9D1D9" />
</td>
<td valign="top">
<img src="https://streak-stats.demolab.com?user=edv-Shin&theme=react&hide_border=true&disable_animations=true&background=0D1117&ring=7F52FF&fire=3DDC84&currStreakLabel=3DDC84&sideLabels=7F52FF&dates=8B949E" />
</td>
</tr>
</table>

<img width="90%" src="https://ghchart.rshah.org/3DDC84/edv-Shin" alt="contribution chart" />

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3DDC84,100:7F52FF&height=120&section=footer" />

</div>
