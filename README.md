# 🐱 MySQL
![image](https://github.com/hyejin192/MySQL/assets/129017064/f91ff445-fd4d-403f-8b5b-f841a049837d)

## 🍒 데이타베이스 생성
![image](https://github.com/hyejin192/MySQL/assets/129017064/50bf2aef-a102-4109-9e4d-6fe3fbcedafd)

## 🐨 테이블 생성
![image](https://github.com/hyejin192/MySQL/assets/129017064/b284505f-e61e-473a-a64d-a2cd26ba0538)

      char : 고정 길이 문자열 데이터 타입 
      항상 지정된 길이의 문자열을 저장 예) CHAR(10)은 항상 10개의 문자를 저장, 만약 문자열이 지정된 길이보다 짧다면 나머지 공간은 공백으로 채워진다.
      
      varchar : 가변 길이 문자열 데이터 타입 
      이는 저장할 문자열의 길이에 따라 공간이 동적으로 조정 예) VARCHAR(10)은 최대 10개의 문자를 저장할 수 있지만, 실제로 저장된 문자열의 길이에 따라 공간이 조정
      따라서, 문자열이 짧을 경우에는 실제 길이만큼의 공간만 차지
      
      not null : 빈공간을 허용x 사용자가 유효한 값을 갖게 함
      primary key : 중복된 값을 허용x

## 🎱 데이타 입력하기
![image](https://github.com/hyejin192/MySQL/assets/129017064/51d008d7-4a6d-42c1-a664-9342da775e25)

      각각 INSERT 줄에 커서를 놓고 번개모양 누른 후 SELECT문 끝에 커서를 놓고 번개모양 누르기
      
## 🐤 데이타 삭제하기
![image](https://github.com/hyejin192/MySQL/assets/129017064/81391f80-bfb6-464e-9dc9-6e4d023a74f1)

      각각 DELETE 줄에 커서를 놓고 번개모양 누른 후 SELECT문 끝에 커서를 놓고 번개모양 누르기
      (다시 INSERT줄에 커서를 놓고 번개모양을 누르면 다시 생성됨)
### 대문자 변형하기      
![image](https://github.com/hyejin192/MySQL/assets/129017064/7fb915cd-9943-4bdf-a88a-55e838714662)

![image](https://github.com/hyejin192/MySQL/assets/129017064/ea2be7a7-b612-4fc2-aec8-6987c8bece65)

      한번에 여러개 추가할 땐 ,찍고 요소 추가
      

![image](https://github.com/hyejin192/MySQL/assets/129017064/51c04d65-7ee7-4013-8498-61aa75099e39)

![image](https://github.com/hyejin192/MySQL/assets/129017064/a2cf80ba-5623-4b37-b967-940a5965e0e1)

## 쿼리문의 순서(구해오리)
SELECT 열이름 >
FROM 테이블이름 >
WHERE 조건문 >
GROUP BY 열이름 >
HAVING 조건문 >
ORDER BY 열이름 >
LIMIT 숫자; >

![image](https://github.com/hyejin192/MySQL/assets/129017064/c97d1b0b-0a57-488b-9d1e-726681965855)

      LIMIT 숫자; : 출력하는 갯수를 제한
![image](https://github.com/hyejin192/MySQL/assets/129017064/f6ac3fa7-0296-4aa4-a76f-43f3e3c3b2c1)


# 포트죽이기(실패)
![image](https://github.com/hyejin192/MySQL/assets/129017064/502b2b2c-85e5-4645-a33c-837a30573c73)

      netstat -a -o
![image](https://github.com/hyejin192/MySQL/assets/129017064/73d0388f-8ad9-4bc2-bcfe-1ffe380589a5)

      taskkill /f /pid 5056

# mysql 삭제 후 실행
![image](https://github.com/hyejin192/MySQL/assets/129017064/d45be076-bbc4-433e-bdfe-17098032c8a3)

      c폴더 안에 pagedata 안에 있는 sql을 지우고 cmd에 sc delete mysql 실행







