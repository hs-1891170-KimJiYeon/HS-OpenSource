# OPENSOURCE(8)\_4,9_report

## 1. 서비스 소개

(주제에대한 설명)

## 2. 유사서비스 분석

### 2.1 유사서비스 분석

(왓차피디아)

### 2.2 유사서비스와의 차별점

(wordcloud로 시각화 가능..)

## 3. 시스템 구조

### 3.1 추천 시스템

### 3.2 검색 시스템

### 3.3 라이선스 문제

사용한 소프트웨어 중 Tensorflow와 SpringBoot 의 경우 Apache2.0 라이선스를 사용하고 있고, KoNLPy는 GPL3.0, MariaDB는 GPL2.0 라이선스를 사용하고 있다.
Apache 라이선스는 GPL 라이선스와 양립하지 못하게 되지만 GPL3.0 은 GPL2.0의 문제를 해소하여 Apache 라이선스와 양립할 수 있게 되었다.
그러나 MariaDB의 경우 GPL 2.0 라이선스를 사용하고 있는데 MariaDB 커넥터가 LGPL 라이선스를 사용하고 있어 동적링킹되어 결합한다면 Apache 라이선스와 양립할 수 있다.

## 4. 사용된 오픈소스 소프트웨어

### 4.1 Maria DB

MariaDB는 오픈 소스의 관계형 데이터베이스 관리 시스템(RDBMS)이다. MySQL과 동일한 소스 코드를 기반으로 하며, GPL v2 라이선스를 따른다. 오라클 소유의 현재 불확실한 MySQL의 라이선스 상태에 반발하여 만들어졌다.

MariaDB는 MySQL과 소스코드를 같이 하므로 사용방법과 구조가 MySQL과 동일하다. 이름만 다르지 명령어나 사용방법 모두 MySQL과 동일하다. 편의를 위해 MariaDB는 동일한 MySQL 버전과 바이너리 드롭인 교체를 지원한다.

근본적인 차이점은 MariaDB는 GPL v2 라이선스를 따르는 순수한 오픈소스 프로젝트이기에 오라클로부터 자유롭다. MariaDB의 모든 코드는 GPL, LGPL, LPGL, BSD의 라이선스로 만들어져 있다. 누구나 필요로 하면 커뮤니티를 통해 MariaDB를 내려받아 쓸 수 있다.

### 4.2 KoNLPy

### 4.3 Tensorflow

### 4.4 WordCloud

WordCloud란 문서의 키워드, 개념 등을 직관적으로 파악할 수 있도록 핵심 단어를 시각화하는 기법이다. 예를 들면 많이 언급될수록 단어를 크게 표현해 한눈에 들어올 수 있게 하는 기법 등이 있다. 주로 빅데이터를 분석할 때 데이터의 특징을 도출하기 위해 활용한다.

### 4.5 ElasticSearch

### 4.6 SpringBoot

### 4.7 React

### 4.8 React Star Rating
