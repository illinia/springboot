# Chapter 01
## 인텔리제이로 스프링 부트 시작하기

세팅이 바뀌어 블로그 참고

https://jojoldu.tistory.com/539

- build.gradle 에서
    ```
  dependencies {
    testImplementation 'org.junit.jupiter:junit-jupiter-api:5.3.1'
    testRuntimeOnly 'org.junit.jupiter:junit-jupiter-engine:5.3.1'
  }
  ```
  는 제거해준다

# Chapter 02
## 스프링 부트에서 테스트 코드를 작성하자

- Lombok 애노테이션
  
  https://www.daleseo.com/lombok-popular-annotations/

- Lombok 애노테이션 생성자 오류

  https://github.com/jojoldu/freelec-springboot2-webservice/issues/78

# Chapter 03
## 스프링 부트에서 JPA로 데이터베이스 다뤄보자

- Dto

  https://tecoble.techcourse.co.kr/post/2021-04-25-dto-layer-scope/

- Builder 패턴

  https://readystory.tistory.com/121

- 트랜잭션 스크립트 패턴 vs 도메인 모델 패턴

- DI(Dependency Injection), Bean, Ioc(Inversion of Control)

  https://velog.io/@gillog/Spring-DIDependency-Injection

- @Autowired, @RequiredArgsConstructor, @NoArgsConstructor

  https://life-with-coding.tistory.com/433
  https://medium.com/webeveloper/requiredargsconstructor-를-이용한-의존성-주입-dependency-injection-4f1b0ac33561
  https://invicr.github.io/2020/03/31/Spring-NoArgsConstructor-RequiredArgsConstructor-AllArgsConstructor/

- 싱글톤 패턴

  https://velog.io/@jaeeunxo1/spring-singleton
  https://hongchangsub.com/springcore5/

- @RestController

  https://doctorson0309.tistory.com/664

- @RequestMapping

  https://0penster.tistory.com/24

- @Service

  https://baek-kim-dev.site/64

- @Transactional

  https://tecoble.techcourse.co.kr/post/2021-05-25-transactional/

- @HttpEntity, @RequestEntity, @ResponseEntity, @TestRestTemplate

  https://easybrother0103.tistory.com/64

- @MappedSuperclass, @EntityListeners, @AuditingEntityListener

  https://ict-nroo.tistory.com/129
  https://webcoding-start.tistory.com/53

# Chapter 04
## 머스테치로 화면 구성하기

- @Transactional(readOnly = true), 영속성 컨텍스트

  https://willseungh0.tistory.com/75
  https://velog.io/@seongwon97/Spring-Boot-영속성-컨텍스트Persistence-Context

- Stream, collect

  https://codechacha.com/ko/java8-stream-collect/

# Chapter 05
## 스프링 시큐리티와 OAuth 2.0으로 로그인 기능 구현하기

- @GeneratedValue

  https://gmlwjd9405.github.io/2019/08/12/primary-key-mapping.html

- @HttpSession

  https://lindarex.github.io/concepts/java-httpsession-introduction/

- meta-annotation

  https://velog.io/@gillog/Spring-Annotation-정리
  
- @WithMockUser

  https://shinsunyoung.tistory.com/94
  https://gaemi606.tistory.com/entry/Spring-Boot-Spring-Security-Test-WithMockUser를-커스터마이징-해서-사용하자

- MediaType

  https://ecsimsw.tistory.com/entry/Spring-MVC-핸들러-미디어-타입-지정
  

# ETC
## Oh-My-Zsh git aliases
https://kapeli.com/cheat_sheets/Oh-My-Zsh_Git.docset/Contents/Resources/Documents/index

## 스프링 주요 어노테이션
https://dev.to/composite/-40c0