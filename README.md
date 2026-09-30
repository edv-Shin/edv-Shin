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

### 운다방 · 운동 습관 · 파트너 매칭 서비스

<sub>**2025.04 ~ 진행 중** · 팀 4명 (Android 1, FE 1, BE 2) · **Android 개발 전담**</sub>
<a href="https://github.com/projects200/android"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white" /></a>
<a href="https://play.google.com/store/apps/details?id=com.project200.undabang"><img src="https://img.shields.io/badge/Google%20Play-414141?style=flat-square&logo=GooglePlay&logoColor=white" /></a>

운동 기록부터 타이머, 파트너 매칭, 피드까지 한 앱에서 이어지는 운동 습관 서비스

| 문제 | 해결 | 결과 |
| :--- | :--- | :--- |
| UI와 비즈니스 로직이 결합돼 단위 테스트가 불가능 | 계층 분리 + 기능 단위 멀티모듈, Gradle로 의존성 방향 강제 | **커버리지 80%**<br/>증분 빌드 3초 |
| Compose 전면 재작성은 리스크가 큼 | 화면 단위 점진 전환 + 공통 컴포넌트 9종을 디자인 시스템으로 추출 | **21개 화면 전환**<br/>7개 중 6개 모듈 |
| 수동 Lint·테스트·배포로 QA 피드백 지연 | GitHub Actions로 PR 자동 테스트 + Firebase / Play Store 배포 | **배포 5분 이내**<br/>기존 30분 |
| 지도 이동 시 카메라 이벤트마다 API 호출 | 마지막 조회 대비 30% 이상 이동했을 때만 재호출 | 중복 요청 제거<br/>광역 조회 차단 |

### 나모 · 모임 일정 · 공유 일기 서비스

<sub>**2024.03 ~ 2025.04** · 팀 9명 (Android 2, iOS 3, BE 2, PM 1, Designer 1) · **Android 파트장**</sub>
<a href="https://github.com/Namo-log/Android"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white" /></a>

그룹을 만들어 모임 일정을 추가하고 모임 공유 일기를 기록하는 서비스

| 문제 | 해결 | 결과 |
| :--- | :--- | :--- |
| View·Controller 겸용으로 화면 코드가 1,000줄까지 비대 | ViewModel 분리 + UI/Domain/Data 레이어 설계 | **코드 40% 감소**<br/>단방향 흐름 |
| 캘린더 라이브러리가 장기 일정 연속 바·주 경계 분할 미지원 | View를 상속해 Canvas로 직접 렌더링, 주 단위 분할·겹침 정렬 | **드로잉 로직 재사용**<br/>개인·모임 공용 |
| 중첩 콜백과 파편화된 예외 처리로 흐름 파악 곤란 | 콜백을 suspend 함수로 전환, Data Source 레이어로 대체 | **에러 추적 단일화**<br/>생명주기 자동 정리 |

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
