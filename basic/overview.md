PostgreSQL은 강력한 오픈소스 객체 관계형 데이터베이스 시스템입니다. 이는 15년 이상의 활발한 개발이 이루어지며 신뢰성, 데이터 무결정 그리고 정확성으로 명성을 얻고 있는 검증된 아키텍처입니다.

이 튜토리얼은 PostgreSQL을 빠르게 시작할 수 있게 도와주며 PostgreSQL 프로그래밍이 편해지도록 해줍니다.

## PostgreSQL이란 무엇인가?

PostgreSQL(포스트-그레스-큐-엘 이라고 읽음)은 세계 각지의 여러 사람들에 의해 개발된 오픈소스 관계형 데이터베이스 시스템(DBMS)입니다. PostgreSQL은 어떤 법인이나 다른 개인 회사에 의해 통제 되고 있지 않으며 소스코드는 무료로 사용할 수 있습니다.

## 약력

처음엔 Postgres라고 불리던 PostgreSQL은 UCB의 Michael Stonebraker라는 컴퓨터 과학 교수에 의해 개발되었습니다. Stonebraker는 1986년에 현재는 Computer Associates가 소유하고 있는 Ingres 프로젝트의 후속 프로젝트로 Postgres 개발을 시작했습니다.

1. 1977-1985: INGRES라는 프로젝트가 개발되었습니다.
    * 관계형 데이터베이스에 대한 개념 증명
    * 1980년에 Ingres 회사 설립
    * 1994년에 Computer Associates이 사감
2. 1986-1994: POSTGRES
    * 객체 지향과 쿼리 언어 Quel에 집중하여 INGRES의 개념을 개발
    * INGRES의 코드 베이스는 POSTGRES의 기반으로 사용되지 않음
    * Illustra로 상용화됨 (IBM이 사간 Infomix에서 사감)
3. 1994 - 1995: Postgres95
    * 1994년에 SQL 지원이 추가됨
    * 1995년에 Postgres95로 릴리즈됨
    * 1996년에 PostgreSQL로 재릴리즈됨
    * PostgreSQL 글로벌 개발팀 설립

## PostgreSQL의 핵심 기능

PostgreSQL은 Linux, Unix (AIX, BSD, HP-UX, SGI IRIX, Mac OS X, Solaris, Tru63) 그리고 Windows를 포함한 모든 주요 운영체제에서 돌아갑니다. 이는 텍스트, 이미지, 소리, 비디오 그리고 C, C++, Java, Perl, Python, Ruby, Tcl 그리고 Open Database Connectivity(ODBC)를 위한 프로그래밍 인터페이스까지 지원합니다.

PostgreSQL은 SQL 표준의 대부분을 지원하며 다음과 같은 많은 모던한 기능들도 제공합니다.

* 복잡한 SQL 쿼리
* SQL 하위 조회 (Sub-select)
* 외래키
* 트리거
* 뷰
* 트랜잭션
* 다중 버전 동시성 제어 (MVCC)
* 스트리밍 복제 (9.0)
* 이중화 (Hot Standby, 9.0)

위에 언급된 기능들을 이해하기 위해 PostgreSQL의 공식 문서를 확인할 수 있습니다. PostgreSQL은 사용자가 다양한 방법으로 확장할 수 있습니다. 예를 들면 다음의 것들을 추가할 수 있습니다.

* 데이터 타입
* 함수
* 연산자
* 집계 함수
* 인덱싱 방법

## 프로시저 언어 지원

PostgreSQL은 사용자가 아무 언어로 코드를 작성할 수 있도록 네가지 표준 프로시저 언어를 지원하며 이는 PostgreSQL 데이터베이스 서버에서 실행 가능합니다. 이 프로시저 언어들은 PL/pgSQL, PL/Tcl, PL/Perl 그리고 PL/Python입니다. 게다가, 다른 비표준 프로시저 언어들인 PL/PHP, PL/V8, PL/Ruby, PL/Java 등등 또한 지원됩니다.
