#메모장 기능 설계

1. 접속 하자마자 메모 전체 목록 조회하기
    1. GET API 사용해서 메모 목록 불러오기
2. 메모 생성하기
    1. POST API 사용해서 메모 신규 생성하기
    2. 생성된 메모 반환
3. 메모 변경하기
    1. PUT API 사용해서 메모 내용 변경하기
    2. 사용자가 클릭한 메모가 DB에 존재하는지 확인하기
    3. 해당 메모 내용 변경
4. 메모 삭제하기
    1. DELETE API 사용해서 메모 삭제하기
    2. 사용자가 삭제하려는 메모가 DB에 존재하는지 확인하기
    3. DB에서 해당 메모 삭제
  
#API 테이블
![image](https://github.com/hyeyoooo/memo/assets/155596443/bb87c5d4-2518-47fe-9b47-907966101f3b)
