# Racing-Game

대략적 기획(변경가능)
1. 게임에 들어가면 인트로 화면이 나온 Touch please, AI 화면 필요
2. 그림 3개에 각각 게임 유형이 있음( 연습모드, 싱글 플레이_(AI로 경주 필요), 멀티 플레이(이거는 생각해봐야할듯)) 누르면 씬 전환

이후는 나중에 생각해보자. 

1. 일단 AI로 인트로 화면을 먼저 만들자. (일단 AI 1장) - 1920:1080 , 16:9 이미지정도 - 대략적으로 완성 - 완료
2. 터치시 새로운 그림이 나오고 가운데에 세개의 그림이 나온다. ( 1장 + 3장????) - AI 이미지 만들어야 한다. - 완료
3. 그림을 클릭하면 각각의 씬으로 이동한다. - 튜토리얼 씬만 로드됨, 다른 씬들도 만들고 연결( 로딩 시간동안 다른 화면 만들게 생각해보자. ) - 다른 맵들도 연결하게 했다.

해야할것
- 쯔구르 영상 공부하던거 찾아보며 응용해보자.
- 인트로에서 각 맵을 넘어가면서 싱글톤 패턴 차에적용(생각해보자.)

- 로딩시 나오는 다른 화면은 나중에 마지막에 생각해보자.
  
 - 일단 게임의 기본 흐름 - 게임시작 - 게임선택 - 몇 초 대기 후 움직이게 조작


유튜브 보고 넣을 것(기능, 기술)
- Lock on 기능 (한 타겟을 바라보게 하는것 - Text도 가능한지 알아보기 ) X
- 스폰 사라지는 효과 ( 일단은 생각 없음 - 오브젝트가 아래, 위에서 순차적으로 생성됨 ) X
- TTS 기능 ( 넣자. 나중에 ) O
- Sky Box 배경 꾸미기 ( 싱글 맵, 멀티 플레이어 맵에 넣자. ) X
- 타임라인 컷씬 ( 인트로, 게임 시작 전, 게임 끝 정도 넣을 생각 중 ) O
- 카메라 방향으로 UI 텍스트 보이기 ( 주행중인 차위에 이름이나 정보 뜨게 ) O
- 스킬 쿨타임( 부스터나 아이템 쭉 생각해보자. ) O 
- 쯔꾸르의 맵이동(케이디님) O ------------------------ 다음 할것 ---------------------------------------
- 오디오, 브금 매니저 ( 어느정도 먼저 만들고 나중에 넣자. ) O
- 차 언덕 오르게 해결하자. ___________________ 오늘할것_____________________

만들어진 부분
- 자동차 기본 조작, 카메라 Follow 기능, 기본 튜토리얼 맵, 싱글맵, 멀티플레이어 맵

앞으로 추가시킬 기능( 바뀔수 있음 )
- 씬전환 시 싱글톤으로 오브젝트 파괴 안 시키기
- 자동차 AI 기능(웨이포인트?)
- 몇 바퀴 돌았는지 세기, 결승점 도착 시 레이싱 종료
- 시작?, 종료? 애니메이션 기능
- 시간 기능
- UI 기능 ( 미니맵, 설정(소리, 화면 비율), RPM은 생각 좀)
 
