# JUnit 애너테이션

| 애너테이션 | 설명 |
|-----------|------|
| @BeforeAll  | 전체 테스트를 시작하기 전 1회 실행. static으로 선언 |
| @BeforeEach | 테스트 케이스를 시작하기 전마다 실행 |
| @Test       | 테스트 케이스 |
| @AfterEach  | 테스트 케이스를 종료하기 전마다 실행  |
| @AfterAll   | 전체 테스트를 마치고 종료하기 전 1회 실행. static으로 선언 |

<br/><br/>

# AssertJ 검증문
assertThat().메서드

| 메서드 이름        | 설명             |
| ---               | ---              |
| isEqualTo(A)      | A 값과 같은지 검증    |
| isNotEqualTo(A)   | A 값과 다른지 검증    |
| contains(A)       | A 값을 포함하는지 검증 |
| doesNotContain(A) | A 값을 포함하지 않는지 검증 |
| startsWith(A)     | A로 시작하는지 검증 |
| endsWith(A)       | A로 끝나는지 검증   |
| isEmpty()         | 비어있는 값인지 검증 |
| isNotEmpty()      | 비어있지 않은 값인지 검증 |
| isPositive()      | 양수인지 검증 |
| isNegative()      | 음수인지 검증 |
| isGreaterThan(1)  | 1보다 큰 값인지 검증 |
| isLessThan(1)     | 1보다 작은 값인지 검증 |

<br/><br/>

# HTTP 주요 응답 코드
| 매핑 메서드              | 설명 |
| ---                     | --- |
| isOk()                  | HTTP 응답 코드가 200 OK 인지 검증 |
| isCreated()             | HTTP 응답 코드가 201 Created 인지 검증 |
| isBadRequest()          | HTTP 응답 코드가 400 Bad Request 인지 검증 |
| isForbidden()           | HTTP 응답 코드가 403 Forbidden 인지 검증 |
| isNotFound()            | HTTP 응답 코드가 404 Not Found 인지 검증 |
| is4xxClientError()      | HTTP 응답 코드가 400번대 응답 코드인지 검증 |
| isInternalServerError() | HTTP 응답 코드가 500 Internal Server Error 인지 검증 |
| is5xxServerError()      | HTTP 응답 코드가 500번대 응답 코드인지 검증 |

