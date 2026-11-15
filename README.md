<p align="center">
  <img src="docs/assets/cover.svg" alt="딸깍엠작 — 엠작하기 전, 회수율부터 비교하세요." width="100%">
</p>

<p align="left">
  <a href="https://github.com/9root3/maple-mvp-releases/releases/download/v1.0.3/Maple-MVP-1.0.3-win-x64.exe">
    <img src="docs/assets/download-windows.svg?v=1.0.3&amp;layout=2" alt="Windows용 다운로드 v1.0.3" width="350" height="104" align="left">
  </a>
  <a href="#사용법"><img src="docs/assets/nav-guide.svg" alt="사용법" width="158" height="28"></a><br>
  <a href="docs/FAQ.md"><img src="docs/assets/nav-faq.svg" alt="자주 묻는 질문" width="158" height="28"></a><br>
  <a href="https://github.com/9root3/maple-mvp-releases/releases"><img src="docs/assets/nav-releases.svg" alt="변경 내역" width="158" height="28"></a>
</p>
<br clear="all">

![딸깍엠작 대시보드 — 예시 캐릭터와 예시 시세로 촬영한 화면](docs/images/dashboard-frame.svg)

<sub>화면의 캐릭터·가격·검색 잔여 횟수는 사용법 설명을 위한 예시입니다.</sub>

캐시 아이템 판매·메소마켓·메포 선물식의 **현금 회수율**을 비교하는 앱입니다.
충전 할인율과 경매장 수수료를 반영해, 쓴 현금에서 얼마나 회수할 수 있는지 보여 줍니다.

## 사용법

### 1. 설치하고 로그인하기

위 다운로드 버튼으로 설치 파일을 받아 실행합니다.
설치가 끝나면 바탕화면의 **딸깍엠작**을 켜 주세요.

오른쪽 위 **로그인**을 누른 뒤, 열린 경매장 창에서 로그인하고 사용할 캐릭터를 선택합니다.
연결되면 경매장 창이 숨겨지고 대시보드로 돌아옵니다.
자동으로 연결되지 않으면 **연결 확인**을 눌러 주세요.

![첫 실행 화면의 로그인·연결 확인 버튼](docs/images/connection-frame.svg)

### 2. 내 조건 입력하기

| 입력 항목 | 입력 예시 | 안내 |
| :--- | :--- | :--- |
| <img src="docs/assets/field-cash.svg" alt="메소 현금 시세" width="190" height="30"> | **1,400**<br><sub>원 / 1억 메소</sub> | 현재 거래하는 메소 현금 가격을 입력합니다. |
| <img src="docs/assets/field-discount.svg" alt="캐시 충전 할인율" width="190" height="30"> | **7%** | 실제 충전 할인율입니다. 할인 없이 충전하면 <strong>0%</strong>로 둡니다. |
| <img src="docs/assets/field-fee.svg" alt="MVP 수수료" width="190" height="30"> | **켬 3%** · **끔 5%** | 경매장 수수료 3%를 적용받으면 켭니다. |
| <img src="docs/assets/field-market.svg" alt="메소마켓 기준 매수가" width="190" height="30"> | **2,134**<br><sub>메포 / 1억 메소</sub> | 시세 조회 때 [메차트](https://maplechart.com/mesomarket.html) 매수가로 갱신됩니다. |
| <img src="docs/assets/field-gift.svg" alt="메포 선물식" width="190" height="30"> | **6,800**<br><sub>원 / 1만 메포 선물</sub> | 1만 메포를 선물할 때 받는 현금 가격입니다. |

<img src="docs/images/settings-frame.svg" alt="할인율·MVP 수수료·메소 시세를 입력한 예시" width="428">

입력값을 바꾸면 회수율은 바로 다시 계산됩니다.

### 3. 시세 조회하고 비교하기

**시세 조회**를 누르면 본인 서버의 최저 호가와 최근 3일 체결 내역을 가져옵니다.
품목명·현재 최저 호가·평균 판매가 제목을 누르면 정렬 방향이 바뀌고,
아래 <strong>더보기 +</strong>를 누르면 나머지 품목도 볼 수 있습니다.

크레딧샵 품목도 체크 여부와 관계없이 함께 조회·저장합니다.
**크레딧 회수 반영**을 켜면 크레딧당 회수액이 가장 높은 품목을 골라 회수율에 더합니다.
<img src="docs/images/credit-frame.svg" alt="크레딧 회수 품목과 비교 목록 일부를 펼친 예시" width="428">

전체 시세 조회는 정상 완료 기준 **32회**를 사용합니다. 실패 후 재시도에는 추가 횟수가 들 수 있습니다.
입력값 변경·정렬·크레딧 체크에는 검색 횟수를 사용하지 않습니다.

조회 제한이나 화면 표시가 궁금하면 [자주 묻는 질문](docs/FAQ.md)을 참고해 주세요.

## 업데이트

**앱을 켜면 새 버전 확인과 다운로드는 자동으로 진행됩니다. 설치는 다운로드가 끝난 뒤 앱을 종료할 때 진행됩니다.**

- **지금 적용:** ‘준비 완료’가 뜨면 **종료하고 업데이트**를 누르세요. 앱을 닫고 설치한 뒤 다시 실행합니다.
- **나중에 적용:** 계속 사용하다가 앱을 닫으면 자동으로 설치됩니다. 다음에 켤 때 새 버전으로 실행됩니다.

**업데이트 확인**은 앱을 켜 둔 동안 새 버전이 나왔는지 다시 확인할 때 쓰는 버튼입니다.

표시된 가격에 실제로 판매된다는 보장은 없습니다. 체결 내역도 함께 확인해 주세요.

NEXON 공식 앱이 아닙니다. 메이플스토리 아이템 이미지의 권리는 NEXON에 있습니다.
