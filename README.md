# auto_down_forwin

### 윈도우 설치 이후 필수 프로그램(주관적)을 자동으로 설치 하는게 목적

23.02.01 - explorer 명령어를 활용해 단순히 미리 만들어놓은 명령어를 실행해 다운로드(자동 설치는(x)) -> 일일히 수동 실행 필요

https://www.fmkorea.com/5481328543 // 최초 발상 근원지

https://forgiveall.tistory.com/455 // 초코를 이용한 패키지 설치 가이드

https://chocolatey.org/install // 초코를 shell 프로그램으로 설치

https://dololak.tistory.com/665 // 초코 관련 설명

### 현재 구상 순서
- git hub를 이용해 간단한 링크 접속 후 초코 설치 -> 패키지 설치 -> batch 파일로 일괄 다운로드 후 개별 설치 -> 게임 관련 링크 파일 다운로드

- 위 링크를 참고해서 chocolatey(이하 초코)를 이용해 초코 패키지에 포함된 프로그램들은 자동 다운로드 후 설치
- 초코 패키지에 없는 프로그램의 경우 batch파일을 이용해 일괄 다운로드 후 수동 설치 -> 패키지 리스트와 프로그램 목록 비교하여 확인
- 패키지 리스트에 없는 경우 내가 추가 가능한지 확인
- 게임과 관련된 프로그램 설치 파일 링크를 포함시켜 사용자가 확인 후 개별 설치 수행
  - 게임의 경우 설치 파일의 용량이 크기 때문


## auto_downloader.bat 실행 시 자동으로 설치 파일 다운로드, 이후 개별 설치 필요

### 포함된 프로그램 및 파일 목록
1. 카카오톡 / 메신저
2. 팟플레이어 / 미디어 플레이어
3. 구글 크롬 / 브라우저
4. 꿀뷰 / 이미지 뷰어
5. 반디집 / 압축 프로그램
6. Everything / 윈도우 파일검색 프로그램
7. TidyTabs / 프로그램 창 멀티화
8. KakaoTalkAdBlock / 카카오톡 광고 제거
9. QTTabBar / 폴더 탐색기 멀티화
10. Discord / 게임 메신저
11. Slack / 사내 메신저
12. VSCODE / IDE
13. Notion / 기록 툴
14. Logitech G Hub / 로지텍 기기 제어용
15. Game_list.txt / 게임 관련 프로그램의 링크들

### Game_list
1. 리그오브레전드
2. 로스트아크
3. Steam
4. Origin
5. Battle.net
