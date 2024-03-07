![Spring Boot Logo](https://cdn.inflearn.com/public/files/blogs/1a0fbdae-5d2d-4ef4-a5fc-49a2980d27cf/spring.png)

# 프로젝트 명

스프링 큰 그림 그리기

## 개요

이 프로젝트는 스프링을 사용하여 개발된 애플리케이션입니다. 여기서는 스프링의 기본 구조를 설명하고, 주요 기능을 소개합니다.

## 시스템 요구사항

- **JDK 버전**: JDK 21
- **빌드 도구**: Gradle

## 의존성

이 프로젝트는 다음과 같은 의존성을 포함합니다:

- Spring Web Starter
- Thymeleaf

## 시작하기

이 섹션에서는 로컬 개발 환경에서 프로젝트를 설정하고 실행하는 방법을 설명합니다.

### 설치

1. JDK 21을 설치합니다.
2. 이 프로젝트를 위한 Gradle을 설치합니다.

### 실행

프로젝트를 클론하고 다음 명령어를 사용하여 애플리케이션을 실행합니다:

```bash
./gradlew build
cd build/libs
java -jar hello-spring-0.0.1-SNAPSHOT.jar
