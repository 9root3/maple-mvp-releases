<p align="center">
  <img src="docs/assets/cover.svg" alt="딸깍엠작 — 엠작하기 전, 회수율부터 비교하세요." width="100%">
</p>

<table align="center" role="presentation">
  <tr>
    <td align="center" valign="middle">
      <a href="https://github.com/9root3/maple-mvp-releases/releases/download/v1.0.3/Maple-MVP-1.0.3-win-x64.exe">
        <img src="docs/assets/download-windows.svg?v=1.0.3" alt="Windows용 다운로드 v1.0.3" width="330" height="68">
      </a>
    </td>
    <td align="center" valign="middle">
      <a href="#사용법"><img src="docs/assets/nav-guide.svg" alt="사용법" width="158" height="28"></a><br>
      <a href="docs/FAQ.md"><img src="docs/assets/nav-faq.svg" alt="자주 묻는 질문" width="158" height="28"></a><br>
      <a href="https://github.com/9root3/maple-mvp-releases/releases"><img src="docs/assets/nav-releases.svg" alt="변경 내역" width="158" height="28"></a>
    </td>
  </tr>
</table>

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

| 입력 | 넣을 값 |
| --- | --- |
| 메소 현금 시세 | 1억 메소당 현금 가격 |
| 캐시 충전 할인율 | 실제로 할인받는 비율. 할인 없이 충전하면 0% |
| MVP | 경매장 수수료 3%를 적용받으면 켜고, 일반 5%면 끕니다. |
| 메소 마켓 기준 매수가 | 1억 메소를 사는 데 드는 메포. 시세 조회 때 메차트 값으로 갱신됩니다. |
| 메포 선물식 | 1만 메포를 선물할 때 받는 현금 가격 |

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

새 버전이 있으면 앱에서 내려받습니다. **종료하고 업데이트**로 적용할 수 있고,
직접 확인하려면 앱 아래의 **업데이트 확인**을 누르면 됩니다.
품목 목록은 앱에서 자동으로 갱신합니다.

표시된 가격에 실제로 판매된다는 보장은 없습니다. 체결 내역도 함께 확인해 주세요.

NEXON 공식 앱이 아닙니다. 메이플스토리 아이템 이미지의 권리는 NEXON에 있습니다.
