# EnAtlas
EnAtlas는 Spring framework 기반으로 만들어진 개인 또는 기업의 application 의 소스를 분석하여 효과적으로 내부 구성과 주변의 연결사항을 확인할 수 있는 application 입니다. 

설치방법과 사용방법은 WIKI 를 참고 하시기 바랍니다.
https://github.com/Wiseple/EnAtlas_community/wiki/EnAtlas-Home

최신 버전 : 13mm
수정사항
- application 구성 페이지의 사이즈가 큰 경우 rendering 되지 않은 오류 수정
- Mybatis SqlSessionTemplate 호출에 의한 연동 정보에 MODEL 생성
- Model rebuild시 cache에서 삭제
- structure 화면애서 팝업으로 새창 띄우기 기능 제공