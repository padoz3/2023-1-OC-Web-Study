#1주차 복습
1. URL : 프로토콜 + DNS(Domain Name System) 주소
> 네트워크 상에서 리소스(웹 페이지, 이밎, 동영상 등의 파일) 위치한 정보를 나타냄
구조: 1) scheme: 사용할 프로토콜. http or https
     2) user, password : 서버에 있는 데이터에 접근하기 위한 사용자의 이름과 비밀번호
     3) host, port : 접근할 대상(서버)의 호스트명과 포트 번호
     4) path : 접근할 대상(서버)의 경로에 대한 상세한 정보
     5) query : 접근할 대상에 전달하는 추가적인 정보 (파라미터)
     6) fragment : 메인 리소스 내에 존재하는 서브 리소스에 접근할 때 이를 식별하기 위한 정보
     :scheme: :hosts: :url-path: :query:

2. URN : Uniform Resource Name
> 프로토콜을 제외하고 리소스의 name을 가리키는 데 사용됨
> 리소스 접근 방법과 웹 상의 위치가 표기되지 않음

* URI, URN 차이점
: URL: 리소스를 어떻게 얻을 것이고 어디에서 가져와야하는지 명시함
  URN: 경로와 리소스 자체를 특정하는 것을 목표로 함


출처 : https://velog.io/@younoah/uri-url-urn

#2주차 복습
1. 깃 = 파일의 변경사항을 추적하고 협업작업을 조율해주는 무언가. 

2. 깃 명령어
    git add: staging 영역에 변화를 쌓아둠.
    * staging area : 다양한 변화를 논리적으로 엮어 이름을 짓기 위해 변화를 쌓는 공간

    git commit : 쌓아둔 변화들의 이름을 짓는 명령어
    
    repository : 저장소

    directory : 폴더

    push : 커밋한 내용을 밀어넣을 수 있음. 밀어놓은 코드는 서버에 올라감 > 공유 가능
