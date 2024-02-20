# :camping: Spring &  React로 만든 캠핑 전문 사이트 Camply

## :clipboard: 개발환경
* Window 10
* MacOS Sonoma
* Eclipse IDE
* IntelliJ
* Visual Studio Code
* Postman
* GitHub
* Slack

## :clipboard: 사용 기술
### 백엔드
#### Spring boot
* JAVA 17
* Spring
* Spring Boot Security
* MyBatis

#### Build tool
* Maven

#### Database
* Oracle
* Redis

#### AWS
* EC2
* RDS
* Route 53
* Certificate Manager

### 프론트엔드
* Javascript
* Thymeleaf
* jQuery
* BootStrap

## :clipboard: 주요 키워드
* REST API
* 시큐리티
* 배치
* 스케줄링
* HTTP 통신
* JPA
* 페이징
* 트랜잭션
* 예외처리
* Git 버전관리
* AWS EC2 배포

## :clipboard: 성능 테스팅 도구
* K6
* Grafana
* InfluxDB

## :clipboard: 로그 분석 도구
* ELK Stack
  * Elasticsearch, Logstash, Kibana, Filebeats

## :link: [Contribution](https://github.com/KHfive-guys/camply-main/tree/master)
| [FrontEnd]     | [쇼핑몰]    | [쇼핑몰]   | [캠핑장 예약]     | [캠핑장 예약]  |
|:-----------------------------------------:|:----------------------------------------------:|:-------------------------------------------:|:----------------------------------------:|:----------------------------------------------------:|
| ![Shin](https://github.com/rjswh0503.png) | ![BEOM](https://github.com/jibum1559.png) | ![chanakoh](https://github.com/chanakoh.png) | ![JongHwan](https://github.com/whdghks9241.png) | ![ExiNni](https://github.com/ExiNni.png) |
| [Shin](https://github.com/rjswh0503)      | [BEOM](https://github.com/jibum1559)    | [chanakoh](https://github.com/chanakoh)    | [JongHwan](https://github.com/whdghks9241)     | [ExiNni](https://github.com/ExiNni)       |


## :link: [ERD 설계](https://github.com/ExiNni/Camply/issues/1)
<img src = "https://private-user-images.githubusercontent.com/86674480/306147128-fa7f1bd7-2175-4cec-8cb9-3037b740b333.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDg0MDgyNjUsIm5iZiI6MTcwODQwNzk2NSwicGF0aCI6Ii84NjY3NDQ4MC8zMDYxNDcxMjgtZmE3ZjFiZDctMjE3NS00Y2VjLThjYjktMzAzN2I3NDBiMzMzLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAyMjAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMjIwVDA1NDYwNVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWIyNWEwNjBkMTBhZmNiODJlMzA0YmExMTQ3OGRiNzVhNzU4MDM0ZjkyOGUyZWI3Njk5NGNlYjQyNjUwYmIwZDkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.wzpt952J4bVjlqgVP1v0bpaDsYaK42JhuM-CS4dtkIg"/>

* ## :factory: [시스템 구조](https://github.com/ExiNni/Camply/issues/2)
<img src = "https://private-user-images.githubusercontent.com/86674480/306148480-bb176320-ca9b-46fb-8f51-a4441a03a211.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDg0MDg2OTcsIm5iZiI6MTcwODQwODM5NywicGF0aCI6Ii84NjY3NDQ4MC8zMDYxNDg0ODAtYmIxNzYzMjAtY2E5Yi00NmZiLThmNTEtYTQ0NDFhMDNhMjExLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAyMjAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMjIwVDA1NTMxN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTM4ZDg5NGZhNDcwOWIwZTNiY2VlYzFiZDQ3ZjVmOTcxNTU4NmRmNWE0MGQwMjJkNTYxZDgyNDQzNzZiOWZmNmUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.belcxydLvnnWxen50T-3gsG54NWkM2VhmtNm2HS65_0"/>
<img src = "https://private-user-images.githubusercontent.com/86674480/306148523-d4096444-ed91-4396-87f6-2096bf463c5d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDg0MDg2OTcsIm5iZiI6MTcwODQwODM5NywicGF0aCI6Ii84NjY3NDQ4MC8zMDYxNDg1MjMtZDQwOTY0NDQtZWQ5MS00Mzk2LTg3ZjYtMjA5NmJmNDYzYzVkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAyMjAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMjIwVDA1NTMxN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWQ3YmU2NDkzY2E1MzIxNWQ4NWUwMTQwNTljOGViOTk0MzU5ZDdlNDAwZjUxYjNmZmJhODhiYzEzODNmMWY3MGUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.7MwGtsIZInD0StCIilfoFAMmXxWDIC8fuTwBwWZVfs0" />

* ## :link: Trouble Shooting
* [trouble shooting](https://github.com/ExiNni/Camply/issues/3)



<!--
## :link: API 서버 (Producer)
* [API 서버](https://github.com/didrlgus/springboot-shoppingmall/tree/master/app/api-server) 

## :link: order 서버 (Consumer)
* [order 서버](https://github.com/didrlgus/springboot-shoppingmall/tree/master/app/order-server)

## :link: product-purchase-count 서버 (Consumer)
* [product-purchase-count 서버](https://github.com/didrlgus/springboot-shoppingmall/tree/master/app/product-purchase-count-server) 

## :link: mail 서버 (Consumer)
* [mail 서버](https://github.com/didrlgus/springboot-shoppingmall/tree/master/app/mail-server)

## :link: product-purchase-count-batch 서버
* [product-purchase-count-batch 서버](https://github.com/didrlgus/springboot-shoppingmall/tree/master/app/product-purchase-count-batch)

## :link: redis-update-batch 서버
* [redis-update-batch 서버](https://github.com/didrlgus/springboot-shoppingmall/tree/master/app/batch-server)

## :link: 공통 모듈
* app 공통 모듈
  * [app 공통 모듈](https://github.com/didrlgus/springboot-shoppingmall/tree/master/app/common)

* lib 공통 모듈
  * [redis 공통 모듈](https://github.com/didrlgus/springboot-shoppingmall/tree/master/lib/redis)
  * [kafka 공통 모듈](https://github.com/didrlgus/springboot-shoppingmall/tree/master/lib/kafka)
  

## :link: redis update 권한 서버
* [redis update 권한 서버 Repository](https://github.com/didrlgus/redis-update-server)

## :link: Rest API 문서
* [shopping mall API 문서](https://github.com/didrlgus/springboot-shoppingmall/issues/58)

## :link: 성능 테스트
* [초기 성능 테스트 결과](https://github.com/didrlgus/springboot-shoppingmall/issues/5)
* [메인화면 API 캐시 적용 전, 후 성능 테스트 비교 결과](https://github.com/didrlgus/springboot-shoppingmall/issues/21)
* [서버를 2대 돌리면 얼마나 더 많은 트래픽을 감당할 수 있을까?](https://github.com/didrlgus/springboot-shoppingmall/issues/46)

-->
