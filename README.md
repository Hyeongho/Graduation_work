# Graduation_work

게임 타이틀: MapleStory_API

유튜브: https://youtu.be/BfgSqetkHCc

깃허브: https://github.com/Hyeongho/MapleStory_API
구글 드라이브: https://drive.google.com/drive/folders/1-3J7kzDiOtqw2OtERFJ6uD_Qgpq5oOLF?usp=sharing

장르: 2D 횡스크롤 RPG
타겟 플레이어: 메이플을 즐겨하는 사람들

메이플스토리에서 보스 패턴을 잘 만들었다고 생각 되는 윌 이라는 보스몬스터를 구현을 했습니다.

맵 에디터를 이용하여 맵 생성이 가능하도록 구현을 했습니다. 
ShardPtr을 사용하여 댕글링포인터 발생 빈도를 줄이고, 메모리 릭 발생을 줄였습니다.
싱글톤패턴을 사용하여 게임 매니저를 한번에 관리하도록 구현을 했습니다.
프로토타입패턴을 이용하여 이펙트나 맵 패턴을 복사를 하면서 랜더링이 가능하도록 구현 했습니다.
더블 버퍼링을 사용하여 맵에 잔상이 남아있지 않도록 구현 했습니다.
키 입력 상태, 버튼 입력상태, AI등을 State 패턴을 사용하여 각각의 상태에 알맞게 동작이 가능 하도록 구현을 했습니다.
맵에 있는 오브젝트, UI들을 각각 vector컨테이너에 담아서 오브젝트는 y값, UI들은 z오더에 의해서 재 정렬을 하여 랜더링이 되도록 구현을 했습니다.
