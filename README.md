# Unity Scripts

Unity로 게임 개발을 할 때 공통적으로 필요한 기능들을 모아놓은 프레임워크   
대부분의 기능들은 Managers를 통해 사용할 수 있으며 별다른 객체 생성 없이 바로 사용할 수 있다.

## Managers 

게임 전역에서 사용할 수 있으며 Input, Resource, UI,Scene, Sound 등의 관리를 도와준다.   
내부적으로는 각 기능별 Manager로 나뉘어져있으며 사용은 Managers를 통해 사용할 수 있다.

### 제공되는 Manager 기능들

- Input Manager : 키보드, 마우스 등 각종 입력에 대한 처리를 도와준다.
- Resource Manager : 게임 오브젝트 관리 및 생성, 삭제를 도와준다.
- UI Manager : 팝업 관리 및 UI를 띄우고 닫는 작업을 도와준다.
- Scene Manager : 씬 관리 및 씬 이동을 도와준다.
- Sound Manager : 사운드 관리 및 재생을 도와준다.
- Pool Manager : 오브젝트 풀링 기능을 제공해준다.
- Data Manager : 외부에서 데이터 파일을 읽어오는 것을 도와준다.

## 설치

1. 현재 레포에서 Scripts를 다운받는다.   
https://downgit.github.io/#/home?url=https://github.com/Eucha09/Unity-Framework/tree/main/GameCore
1. 다운받은 Scripts 폴더를 유니티 프로젝트 Asset 폴더 안에 넣는다.

## 가이드

https://leaf-nylon-1da.notion.site/Unity-Framework-0135706f01a54eee9e1e9c7b368dd9c7