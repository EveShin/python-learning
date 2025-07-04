# Python 프로그래밍 학습 저장소

파이썬 프로그래밍 언어를 체계적으로 학습하고 실무 역량을 개발하기 위한 저장소입니다.

## 학습 목표

- 파이썬 기초 문법과 핵심 개념 완전 이해
- 객체지향 프로그래밍 및 함수형 프로그래밍 패러다임 습득
- 데이터 구조와 알고리즘 구현 능력 향상
- 실무 프로젝트를 통한 문제 해결 경험 축적

## 저장소 구조

```
python-study/
├── notebooks/                  # 학습 노트북
│   ├── 01_fundamentals/
│   │   ├── variables_and_data_types.ipynb
│   │   ├── control_structures.ipynb
│   │   └── functions_and_scope.ipynb
│   ├── 02_data_structures/
│   │   ├── lists_and_tuples.ipynb
│   │   ├── dictionaries_and_sets.ipynb
│   │   └── string_manipulation.ipynb
│   ├── 03_object_oriented/
│   │   ├── classes_and_objects.ipynb
│   │   ├── inheritance_and_polymorphism.ipynb
│   │   └── advanced_oop_concepts.ipynb
│   ├── 04_advanced_topics/
│   │   ├── decorators_and_context_managers.ipynb
│   │   ├── generators_and_iterators.ipynb
│   │   └── concurrency_and_async.ipynb
│   └── 05_libraries/
│       ├── standard_library.ipynb
│       ├── numpy_fundamentals.ipynb
│       └── pandas_basics.ipynb
├── projects/                   # 완성된 프로젝트
│   ├── calculator/
│   ├── text_analyzer/
│   ├── data_processor/
│   └── web_scraper/
├── exercises/                  # 연습 문제
│   ├── basic_problems.ipynb
│   ├── algorithm_challenges.ipynb
│   └── coding_interviews.ipynb
├── utils/                      # 유틸리티 모듈
│   ├── data_utils.py
│   ├── file_utils.py
│   └── testing_utils.py
└── documentation/              # 학습 문서
    ├── concepts_summary.md
    ├── best_practices.md
    └── resources.md
```

## 학습 계획

### 1단계: 기초 문법 (1-3주)
**핵심 개념**
- 변수, 데이터 타입, 메모리 관리
- 제어 구조: 조건문과 반복문
- 함수: 정의, 매개변수, 반환값
- 예외 처리 및 디버깅

**핵심 실습**
- 기본 계산기 구현
- 텍스트 처리 유틸리티
- 데이터 검증 스크립트

### 2단계: 자료구조 (4-5주)
**핵심 개념**
- 내장 자료구조: 리스트, 튜플, 딕셔너리, 집합
- 문자열 조작 및 정규표현식
- 파일 입출력 연산
- 데이터 직렬화 (JSON, CSV)

**핵심 실습**
- 자료구조 성능 비교 분석
- CSV 데이터 처리기
- 로그 파일 분석기

### 3단계: 객체지향 프로그래밍 (6-8주)
**핵심 개념**
- 클래스, 객체, 인스턴스화
- 상속, 다형성, 캡슐화
- 특수 메소드 및 연산자 오버로딩
- 디자인 패턴 및 SOLID 원칙

**핵심 실습**
- 은행 시스템 시뮬레이션
- 게임 개발 프레임워크
- 도서관 관리 시스템

### 4단계: 고급 주제 (9-11주)
**핵심 개념**
- 데코레이터와 메타클래스
- 컨텍스트 매니저와 제너레이터
- 동시성: 스레딩과 asyncio
- 패키지 관리 및 가상환경

**핵심 실습**
- 성능 모니터링 데코레이터
- 비동기 웹 스크래퍼
- 커스텀 패키지 개발

### 5단계: 라이브러리 활용 (12-14주)
**핵심 개념**
- 표준 라이브러리 모듈
- NumPy 수치 연산
- Pandas 데이터 조작
- 테스팅 프레임워크 (unittest, pytest)

**핵심 실습**
- 데이터 분석 파이프라인
- 과학 계산 애플리케이션
- 종합 테스트 스위트

## 주요 프로젝트

### 프로젝트 1: 고급 계산기
**목표**: 수식 파싱, 메모리 기능, 단위 변환을 포함한 과학 계산기
**기술**: 고급 함수 설계, 예외 처리, 사용자 인터페이스

### 프로젝트 2: 데이터 분석 도구
**목표**: 통계 분석 및 시각화 기능을 갖춘 CSV/JSON 데이터 처리기
**기술**: 파일 처리, 자료구조, 수학적 연산

### 프로젝트 3: 웹 스크래핑 프레임워크
**목표**: 데이터 정제 및 내보내기 기능을 갖춘 설정 가능한 웹 스크래퍼
**기술**: HTTP 요청, HTML 파싱, 데이터 지속성

### 프로젝트 4: 객체지향 게임 엔진
**목표**: 엔티티 시스템과 충돌 감지를 포함한 기본 2D 게임 엔진
**기술**: OOP 설계, 성능 최적화, 모듈형 아키텍처

## 핵심 기술 역량

### 프로그래밍 패러다임
- 절차적 프로그래밍
- 객체지향 프로그래밍
- 함수형 프로그래밍 개념
- 디자인 패턴 구현

### 코드 품질
- PEP 8 스타일 준수
- 포괄적 문서화
- 단위 테스트 및 TDD
- 코드 리뷰 관행

### 개발 도구
- Git 버전 관리
- 가상환경 관리
- IDE 설정 및 디버깅
- 패키지 배포

## 학습 자료

### 핵심 교재
- "Effective Python" - Brett Slatkin
- "Python Tricks" - Dan Bader
- "Fluent Python" - Luciano Ramalho
- Python 공식 문서

### 온라인 강의
- Real Python 튜토리얼
- Python.org 공식 튜토리얼
- Automate the Boring Stuff with Python
- Python Crash Course

### 연습 플랫폼
- LeetCode (알고리즘 문제)
- HackerRank (문제 해결)
- Codewars (코드 카타)
- Project Euler (수학 문제)

## 개발 환경

```bash
# Python 3.9+ 설치
python --version

# 가상환경 생성
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# 필수 라이브러리
pip install jupyter pandas numpy matplotlib
pip install pytest black flake8
```

## 진도 관리

### 주간 목표
- 1-3주: 기본 문법 완료
- 4-5주: 자료구조 마스터
- 6-8주: OOP 프로젝트 구현
- 9-11주: 고급 기능 개발
- 12-14주: 라이브러리 통합 및 최적화

### 체크포인트
- 각 단계별 핵심 개념 이해 확인
- 실습 프로젝트 완성도 평가
- 코드 품질 및 문서화 수준 점검
- 문제 해결 능력 향상도 측정

### 완료 기준
- 완료된 프로젝트: ___개
- 해결한 알고리즘 문제: ___개
- 작성한 테스트 케이스: ___개
- 기여한 오픈소스 커밋: ___개

## 학습 방법

### 효과적 접근법
- 이론 학습 후 즉시 실습 적용
- 코드 리뷰 및 리팩토링 연습
- 페어 프로그래밍 및 협업 경험
- 지속적인 문서화 및 정리

### 문제 해결 방법
- 요구사항 분석 및 설계
- 단계별 구현 및 테스트
- 성능 측정 및 최적화
- 코드 품질 개선

---