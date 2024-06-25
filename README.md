# 출석부 프로젝트

## client폴더는 프론트 작업공간입니다.

    - service에서 데이터를 요청합니다.
        studnetAdd : 학생 추가 요청
        studnetDel : 학생 삭제 요청
        allGet : 출석부 데이터 요청

## server폴더는 백엔드 작업공간입니다.

    - 프로젝트 구조상 미들웨어, 라우팅은 구현하지 않고 컨트롤러만 구현할 예정입니다.
    - controller 폴더에 각 서버에서 처리할 업무를 정의할 예정입니다.
    - HTTP 요청은 GET, POST, DELETE 를 사용하여 각 데이터 읽기, 데이터 추가, 데이터 삭제 처리를 진행할 예정입니다.
    - 서버에서 직접 데이터베이스를 생성하고 샘플데이터를 추가할 예정입니다. (런타임 시 초기에 데이터베이스를 생성하고 샘플데이터를 추가하는 방식)

    출석부 불러오기 = 데아터 전체에서 필터링
    학생 추가하기 = 사용자가 입력한 학생 데이터 추가
    학생 삭제하기 = 사용자가 삭제한 학생 데이터를 찾고 삭제

    - 정적 데이터는 클라이언트 측에서 관리합니다. /public

- 의존성 설치 - client , server 로 각각 이동하셔서 터미널에 npm install 입력하시면 자동 설치됩니다.
