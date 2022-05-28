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

# Chapter 06
## AWS 서버 환경을 만들어보자

# Chapter 07
## AWS에 데이터베이스 환경을 만들어보자

# Chapter 08
## EC2 서버에 프로젝트를 배포해 보자

# Chapter 09
## 코드가 푸시되면 자동으로 배포해 보자

# Chapter 10
## 24시간 365일 중단 없는 서비스를 만들자

- stream findAny, findFirst 차이

  https://codechacha.com/ko/java8-stream-difference-findany-findfirst/

- 람다식 contains

  http://yoonbumtae.com/?p=2776

# ETC
## Oh-My-Zsh git aliases
https://kapeli.com/cheat_sheets/Oh-My-Zsh_Git.docset/Contents/Resources/Documents/index

## 스프링 주요 어노테이션 
https://dev.to/composite/-40c0

## 스크립트 
```text
#!/bin/bash -> 스크립트 시작

VALUE=/home/ec2-user/app/step2 -> 경로 변수

echo -> 출력

pgrep -fl -> 명령어 경로 출력
    ps + grep 합친 명령어
    ps: 현재 실행중 프로세스 목록
    grep: 텍스트에서 원하는 문자열 찾아 출력
    
awk -> 파일로부터 레코드 선택, 조작 하는 목적

if 문
    if [ -z "$CURRENT_PID" ]; then
    문자열 길이가 0이면
    else
fi

kill -15 작업 종료 -9 강제 종료

sleep 5 5초 정지

ls -tr -t: 파일 수정 시간 정렬 -r: 내림차순

tail -n 1 -> 마지막 행 기준 일부 출력 명령어, 마지막 1라인

chmod +x $JAR_NAME -> 파일 모드 변경
https://recipes4dev.tistory.com/175

nohup -> 세션 연결 종료시에도 프로그램 종료 안되게
nohup $JAR_HOME > $REPOSITORY/nohup.out 2>&1 &
    -> 1번째 파일 로그를 2번째 파일에, 에러도 출력과 같은 파일에
```