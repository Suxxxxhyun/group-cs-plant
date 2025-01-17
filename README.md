## Contents
- [운영체제](#1-운영체제)
- [데이터베이스](#2-데이터베이스)

---

## 진행 방식
- 작성한 자료는 스터디 시작전 18:00 까지 fork한 repository에 올리고 Pull Requests를 날린다. 
- 방장이 Pull Request를 merge하고 닫는다.
- 발표 당일 정리한 자료를 바탕으로 내용을 실제 면접처럼 진행한다.
  - 발표는 매주 목요일 저녁 8시에 진행한다.
  - 한명이 면접자, 두명이 면접관으로 진행한다.
  - 기존에 있는 질문을 바탕으로 면접을 진행하되, 기존에 없던 질문도 면접을 진행할 수 있다.
- 당일의 스터디가 끝나고 나면 스터디에서 나왔던 질문 및 추가적인 질문을 Issues에 등록한다.
- 브랜치 관리 방법
  fork -> main 브랜치로부터 발표 파트에 대한 브랜치 생성 -> 파일 업로드 -> PR -> merge

---

## 네이밍 규칙
### 파일명 컨벤션
- 방장이 폴더를 생성하면, 그에 따라 "이름.md" 형식으로 파일명을 기재한다.
  - ex) 박수현.md

### PR 컨벤션
- 'OS_질문번호 아이템명 이름'
  - ex) OS_17,18 가상메모리/페이징/세그멘테이션 제출 [박수현]

### 커밋 컨벤션
- "docs:아이템명_이름" 형식을 유지한다. 
  - 예시) "docs:시스템콜_박수현"

---

## 1. 운영체제

|            아이템             |                                                                                                                                                                                                     발표자료                                                                                                                                                                                                     |
|:--------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|         SystemCall         |                      [박수현](https://github.com/cs-learning-study/blog-study/blob/main/os/system_call/os_Q1_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/blog-study/blob/main/os/system_call/os_Q1_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/blog-study/blob/main/os/system_call/os_Q1_%EA%B3%BD%EB%8F%99%ED%98%84.md)                      |
|         Interrupt          |                         [박수현](https://github.com/2024-pass-backend/blog-study/blob/main/os/interrupt/os_Q2_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/blog-study/blob/main/os/interrupt/os_Q2_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/blog-study/blob/main/os/interrupt/os_Q2_%EA%B3%BD%EB%8F%99%ED%98%84.md)                         |
|          Process           |                            [박수현](https://github.com/2024-pass-backend/blog-study/blob/main/os/process/os_Q3_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/blog-study/blob/main/os/process/os_Q3_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/blog-study/blob/main/os/process/os_Q3_%EA%B3%BD%EB%8F%99%ED%98%84.md)                            |
|   Process Address Space    |        [박수현](https://github.com/2024-pass-backend/blog-study/blob/main/os/process-adress-space/os_Q4_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/blog-study/blob/main/os/process-adress-space/os_Q4_%EC%9E%84%EC%84%B1%EC%A4%80.md)  / [곽동현](https://github.com/2024-pass-backend/blog-study/blob/main/os/process-adress-space/os_Q4_%EA%B3%BD%EB%8F%99%ED%98%84.md)        |
|         Scheduler          |                         [박수현](https://github.com/2024-pass-backend/blog-study/blob/main/os/scheduler/os_Q5_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/blog-study/blob/main/os/scheduler/os_Q5_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/blog-study/blob/main/os/scheduler/os_Q5_%EA%B3%BD%EB%8F%99%ED%98%84.md)                         |
|       Context Switch       |                 [박수현](https://github.com/2024-pass-backend/blog-study/blob/main/os/context-switch/os_Q6_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/blog-study/blob/main/os/context-switch/os_Q6_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/blog-study/blob/main/os/context-switch/os_Q6_%EA%B3%BD%EB%8F%99%ED%98%84.md)                  |
| CPU Scheduling Algorithms  | [박수현](https://github.com/2024-pass-backend/blog-study/blob/main/os/cpu-scheduling-algorithms/os_Q7_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/blog-study/blob/main/os/cpu-scheduling-algorithms/os_Q7_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/blog-study/blob/main/os/cpu-scheduling-algorithms/os_Q7_%EA%B3%BD%EB%8F%99%ED%98%84.md) |
|     Mutex & Semaphore      |                [박수현](https://github.com/2024-pass-backend/blog-study/blob/main/os/mutex-semaphore/os_Q8_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/blog-study/blob/main/os/mutex-semaphore/os_Q8_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/blog-study/blob/main/os/mutex-semaphore/os_Q8_%EA%B3%BD%EB%8F%99%ED%98%84.md)                |
|          DeadLock          |                          [박수현](https://github.com/2024-pass-backend/blog-study/blob/main/os/deadlock/os_Q9_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/blog-study/blob/main/os/deadlock/os_Q9_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/blog-study/blob/main/os/deadlock/os_Q9_%EA%B3%BD%EB%8F%99%ED%98%84.md)                           |
|       Virtual Memory       |                   [박수현](https://github.com/2024-pass-backend/cs-plant/blob/main/os/virtual-memory/os_Q17_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/cs-plant/blob/main/os/virtual-memory/os_Q17_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/cs-plant/blob/main/os/virtual-memory/os_Q17_%EA%B3%BD%EB%8F%99%ED%98%84.md)                   |
|   Paging & Segmentation    |             [박수현](https://github.com/2024-pass-backend/cs-plant/blob/main/os/paging-segmenation/os_Q18_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/cs-plant/blob/main/os/paging-segmenation/os_Q18_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/cs-plant/blob/main/os/paging-segmenation/os_Q18_%EA%B3%BD%EB%8F%99%ED%98%84.md)             |
|     Memory-Allocation      |                                                                                                                                [박수현](https://github.com/2024-pass-backend/cs-plant/blob/main/os/memory-allocation/os_Q15_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/cs-plant/blob/main/os/memory-allocation/os_Q15_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/cs-plant/blob/main/os/memory-allocation/os_Q15_%EA%B3%BD%EB%8F%99%ED%98%84.md)                                                                                                                                 |
|         Thrashing          |                                                                                                                                                                                         [박수현](https://github.com/2024-pass-backend/cs-plant/blob/main/os/thrashing/os_Q16_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/cs-plant/blob/main/os/thrashing/os_Q16_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/cs-plant/blob/main/os/thrashing/os_Q16_%EA%B3%BD%EB%8F%99%ED%98%84.md)                                                                                                                                                                                          |
|            TLB             |                                                                                                                                                                                         [박수현](https://github.com/2024-pass-backend/cs-plant/blob/main/os/tlb/os_Q19_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/cs-plant/blob/main/os/tlb/os_Q19_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/cs-plant/blob/main/os/tlb/os_Q19_%EA%B3%BD%EB%8F%99%ED%98%84.md)                                                                                                                                                                                          |
| Page Replacement Algorithm | [박수현](https://github.com/2024-pass-backend/cs-plant/blob/main/os/page-replacement-algorithm/os_Q21_%EB%B0%95%EC%88%98%ED%98%84.md) / [임성준](https://github.com/2024-pass-backend/cs-plant/blob/main/os/page-replacement-algorithm/os_Q21_%EC%9E%84%EC%84%B1%EC%A4%80.md) / [곽동현](https://github.com/2024-pass-backend/cs-plant/blob/main/os/page-replacement-algorithm/os_Q21_%EA%B3%BD%EB%8F%99%ED%98%84.md) |

## 2. 데이터베이스

|        아이템         |              발표자료              |
|:------------------:|:------------------------------:|
|        키 종류        | [박수현](https://github.com/2024-pass-backend/cs-plant/blob/main/db/Q1/%EB%B0%95%EC%88%98%ED%98%84.md) / [전정표]() / [곽동현]() |
|    RDB & NoSQL     |  [박수현]() / [전정표]() / [곽동현]()   |
| Transaction & ACID |            [박수현]() / [전정표]() / [곽동현]()                    |
