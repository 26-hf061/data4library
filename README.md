# data4library  

- API 키 발급 방법  
1. 도서관 정보나루 회원가입   
2. 로그인 후 우상단 [마이페이지] 클릭  
3. 마이페이지 메뉴에서 인증키 선택  
4. 적절한 이용목적 체크 및 개인정보 수집 이용 동의 체크  
5. 수정완료 버튼 클릭  
6. 상태가 승인대기중으로 표시 - 승인까지 시간 소요  
7. 승인 후 발급된 API 키를 복사하여 환경변수에 저장  
💡 참고: 승인 처리에 시간이 걸릴 수 있습니다. 보통 신청 후 익일 오전에 승인됩니다.

- 인기대출 도서 조회  
http://data4library.kr/api/loanItemSrch?authKey=[인증키]&startDt=2017-01-01&endDt=2017-03-27&gender=0&pageNo=1&pageSize=100&format=json  

https://www.data4library.kr/noticeV?cn=201  

https://data4library.kr/noticeV?cn=93  
