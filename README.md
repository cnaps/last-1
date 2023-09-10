### 마이크로서비스 구현
- 도서서비스(https://github.com/cnaps/last-1/BookMS)
- 대여서비스(https://github.com/cnaps/last-1/RentalMS)
- 회원서비스(https://github.com/cnaps/last-1/MemberMS1)
- 베스트도서서비스(https://github.com/cnaps/last-1/BestBookMS)


- 카프카(https://github.com/cnaps/Infra)
  
  - 카프카,주키퍼
  ```
  cd dc
  docker-compose -f docker-compose_kafka1.yml up -d
  ```
  - 카프카 UI
  ```
  cd dc
  docker-compose -f docker-compose_ui.yml up -d
  ```
   - MongoDB
  ```
   docker run -d -p 27017:27017 --name mongodb mongo
  ```
