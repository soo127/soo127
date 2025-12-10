
<!--
**soo127/soo127** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## 👋 방문해주셔서 감사합니다.
저는 Swift 언어를 활용하여 iOS 앱 개발을 하고 있는, 개발자 이상수라고 합니다.

아직 부족한 부분도 많고 지칠 때도 종종 있지만, 맡은 기능에 끝까지 매달려 구현해냈을 때의 경험과 성취감으로 성장하고 있습니다.

---

## 🚀 Projects

### NowToDo - SwiftUI
- iOS 기본 앱인 '미리 알림'을 모델로 하는 간단한 알림 앱입니다.
- 할 일 추가 / 마감일 저장 / 푸시 알림 설정이 가능합니다.

* **MVVM Pattern**
* **UserDefaults:** 앱을 껐다 켜도 투두 설정 내역은 유지되어야 하기에 사용
* **UserNotifications**

🔗 Repo: https://github.com/soo127/NowToDo

---

### AskWeather — SwiftUI
- iOS 기본 날씨 앱의 핵심 UI/UX를 벤치마크하여 제작한 날씨앱입니다.
- 실시간 위치 기반 날씨 조회 / 도시 검색 기능 / 도시 즐겨찾기 등의 기능을 지원합니다.

* **MVVM Pattern**
* **FileManager**
* **CoreLocation:** 사용자가 현재 위치한 지역을 알아내기 위해 사용
* **MapKit**
* **API:** 공공 데이터 포털 등에서 데이터를 받아와서 활용하기 위해 사용
* **Widget**

🔗 Repo: https://github.com/soo127/AskWeather

---

### TalknLike — UIKit
- 게시글을 올리고 댓글을 통해 서로 소통할 수 있는 앱입니다.
- 팔로우/팔로잉, 게시글 좋아요/댓글 기능과 알림, 프로필 설정 등의 기능을 지원합니다.

* **MVC Pattern:**
* **Combine:** 탭바 구조의 특성상 viewDidLoad()가 재호출되지 않아, 기존 방식으로는 다른 페이지에서 팔로우/언팔로우 상태가 변경되어도 피드 UI가 자동으로 갱신되지 않는 문제가 있었습니다. 따라서 Combine을 도입하여 이를 해결했습니다.
* **Firebase:** 회원가입과 데이터(이용자 별 게시글, 게시글 별 댓글 등)을 위해 사용
* **Supabase:** 프로필 이미지를 저장하기 위해 사용

🔗 Repo: https://github.com/soo127/TalknLike

---

### Tile2048 — SwiftUI  
- 유명한 게임인 2048의 로직을 구현한 게임입니다. 

* **TCA:** 복잡한 게임 로직 상태 관리를 위해 `TCA`의 **State, Action, Reducer**의 가장 기본적인 구조를 도입
* **SwiftLint**
* **UserDefaults:** 보드의 크기 별 최고 점수를 불러올 수 있어야 하므로 사용


🔗 Repo: https://github.com/soo127/Tile2048

---

## 정보
- Email: ss_127@naver.com
- Velog: https://velog.io/@soosu/posts
- GitHub: https://github.com/soo127
