# 프로그래머스 웹 풀스택 사이클 데브코스 7기
## Readme 작성법

### Readme
#### 마크다운 언어 파일

##### 작성내용
1. 완성된 프로그램의 설명
   - 프로그램 사용 방법
   - 레퍼런스
2. 구현중인 프로젝트의 현황
   - 구현된 주요 기능
   - 구현 현황
   - 코드가 해결 해야하는 문제
  
일반 사용자가 개발을 모르더라도 웹에서 텍스트의 가독성을 높히기 위해 꾸밀 수 있도록 하는 기술
즉, 텍스트를 웹 기술로 바꿔주는 하나의 도구인 셈이다.

### 마크다운 주요 목적
- 읽기 쉽게 만들고
- 쓰게 쉽게 만든다.

### 마크다운 사용중인 사이트
- 위키백과, tistory, Notion, Velog, GitHub...etc

## 마크다운 사용법

```markdown
1. 순서가 있는 목록
2. 순서가 있는 목록
3. 순서가 있는 목록

- 순서가 없는 목록
- 순서가 없는 목록
- 순서가 없는 목록
```

<aside>
👉

1. 순서가 있는 목록
2. 순서가 있는 목록
3. 순서가 있는 목록

- 순서가 없는 목록
- 순서가 없는 목록
- 순서가 없는 목록
</aside>


```markup
# 1 제목
## 2 제목
### 3 제목
```

<aside>
👉

# 1 제목

## 2 제목

### 3 제목

</aside>

---

```markup
--- // 문단선 ; 문단 나뉘는 선 생성 (위에)

``` // 코드문

>   // 인용문
```

---

### 버전관리

버전은 유의미한 수정을 말함.
버전관리는 백업 용도, 업무의 안정성

**버전 관리 시스템**

- 버전관리
- 백업 복구
- 협업

종류 ( VCS : Version Control System )

- 로컬 VCS
- 중앙집중식 VCS
- 분산 VCS

### 로컬 VCS

로컬에서 버전 관리 하는 것 ( 내 컴퓨터, 내. 노트북 ) == 혼자 버전 관리 하는 것

내 컴퓨터 안에서만, 협업 X

### 중앙집중식 VCS

중앙 컴퓨터 ( 다른 컴퓨터 ) 에서 대표로 버전 관리

내가 필요한 부분의 파일들만 가져와서 작업 진행

ex) CVS, SVN

### 분산VCS ⭐ 협업 사용 추천

로컬 컴퓨터에서도 저장, 중앙 컴퓨터에서도 저장

프로젝트의 전부를 가져온다. ⇒ 훨씬 더 안정적 / 프로젝트가 꼬일 일이 많지 않고, 풀기 쉬움

ex) Git, Mecurial, Bazaar
