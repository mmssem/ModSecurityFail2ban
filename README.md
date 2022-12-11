# < 🐾자 멍멍쌤의 nginx+ModSecurity+fail2ban 공부 >

## 본 내용은 도커를 이용하여 nginx에 ModSecurity와 fail2ban를 설치하는 것을 기록으로 남긴 것입니다.
### 자세한 내용은 아래 블로그를 참고하시기 바랍니다.
--------------

### no-01
- Nginx + ModSecurity + Fail2ban + Docker => 1. 취약한 웹사이트
- https://mungkhs1.tistory.com/65


### no-02
- Nginx + ModSecurity + Fail2ban + Docker => 2. ModSecurity + Fail2ban 설치
- https://mungkhs1.tistory.com/66


### no-03
- Nginx + ModSecurity + Fail2ban + Docker => 3. Fail2ban 설정 방법
- https://mungkhs1.tistory.com/67


### no-04
- Nginx + ModSecurity + Fail2ban + Docker => 4. Nginx Limit req 설정
- https://mungkhs1.tistory.com/68


### no-05
- Nginx + ModSecurity + Fail2ban + Docker => 5. Dockerhub 이미지 사용
- https://mungkhs1.tistory.com/69


### (참고) 본 소스에서 사용되는 front_nginx의 이미지는 1.1 버전이 아닌 1.2 버전을 사용하시기 바랍니다.
image: mungkhs/nginxwaf:1.2