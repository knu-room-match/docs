## 소프트웨어 요구사항 명세서

## 목차

### 1. (서론) Introduction
#### 1.1. (목적) Purpose

이 소프트웨어의 목적은 사용자의 생활습관, 성격 데이터를 기반으로 적합한 룸메이트를 추천하는 시스템을 개발하는데에 목적이 있습니다. 이를 통해 대학생 커뮤니티에서 빈번하게 발생하는 룸메이트와의 갈등 문제를 사전에 예방하고, 사용자들에게 보다 효율적이고 편리한 룸메이트 매칭 경험을 제공하고자 합니다.

특히, 기존 방식의 불편함(수기로 작성된 체크리스트, 필터링 불가, 일일이 게시글 확인)과 한계를 극복하고자 데이터 기반 추천 알고리즘을 활용하여 신뢰도 높은 매칭을 지원합니다.

#### 1.2. (범위) Product Scope

본 시스템은 경북대학교 기숙사 이용자를 주 사용자로 하며, 다음과 같은 기능과 서비스를 제공합니다

> 1. 사용자 정보 수집 : 생활습관, 성격, 선호사항에 대한 설문을 통해 데이터를 수집
> 2. 추천 알고리즘 : 코사인 유사도를 기반으로 사용자 간의 적합도를 계산하여 룸메이트 후보를 추천
> 3. 필터링 기능 : 원하는 조건 (예. 흡연여부, 기상 및 수면 시간대, 취미 등) 으로 룸메이트 검색 결과를 필터링
> 4. 매칭 기능 : 선택된 룸메이트와 매칭 요청 수락 기능
> 5. 채팅 기능 : 매칭 요청 수락 전 채팅 기능
> 6. 커뮤니티 기능 (선택사항) : 기숙사 공지사항 및 커뮤니티 기능
> 7. 이어살기 기능 (선택사항) : 자취방 이어살기 매칭 기능

