# 24년도 오픈소스SW 과제
# 1. top 명령어
  - top명령어는 시스템의 실시간 프로세스 정보를 모니터링하는데 사용
  - 사용 방법 : top

- [x] 실시간 모니터링 적합
- [ ] 실시간 모니터링 부적합

-출력 예시

![top 명령어 사진](https://github.com/LTaeJun/OpenSource-SW/assets/166844562/e9556be3-3a98-4887-bf93-07ed5a6ed472)

<br>


| 정보 | 설명 |
|---|---|
| `CPU 사용량` | 전체 CPU 사용량과 각 CPU의 사용량 |
| `메모리 사용량` | 총 메모리 사용량, 사용 가능한 메모리, 버퍼/캐시 사용량 |
| `스왑 사용량` | 스왑 공간 사용량 |
| `프로세스 목록` | 프로세스 ID (PID), 사용자 이름 (USER), CPU 사용량, 메모리 사용량, 실행 상태 등의 정보를 포함하는 프로세스 목록 |
<br>

**옵션**
* **q** : 종료
* **h** : 도움말
* **M** : 정렬 기준 변경(ex : 메모리 사용량 기준 정렬)
* **화살표 키** : 화면 이동
<br>

# 2. ps 명령어
  - ps명령어는 시스템에서 실행 중인 모든 프로세스의 정보를 출력
  - top명령어와 달리, ps명령어는 한 번에 모든 정보를 출력하기 때문에 실시간 모니터링에는 적합하지 않음
  - 사용 방법 : ps [옵션]
  
Task Lists
- [ ] 실시간 모니터링 적합
- [X] 실시간 모니터링 부적합
<br>

**옵션**
- **-e** : 모든 프로세스(종료된 프로세스 포함) 출력
- **-f** : 더 자세한 정보 출력(ex : 시작 시간, 환경 변수 등)
- **-u** : 특정 사용자의 프로세스만 출력
<br>

# 3. jobs 명령어
- jobs 명령어는 백그라운드에서 실행중인 작업 목록을 출력
- 각 작업은 백그라운드 작업 ID( BGID )로 식별
- 사용 방법 : jobs
<br>

# 4. kill 명령어
- kill 명령어는 프로세스를 강제로 종료하는데 사용
- 프로세스 ID( PID )를 지정하여 특정 프로세스를 종료하거나, 옵션을 사용하여 여러 프로세스를 동시에 종료할 수 있음
- 사용 방법 : kill [PID]
<br>

**옵션**
- **-9** : 강제 종료 (SIGKILL 신호 전송)
- **-TERM** : 종료 신호(SIGTERM) 전송
<br>

# 5. 마무리 요약

| 명령어 | 기능 |
|---|---|
| `top` | 시스템 프로세스 정보 모니터링 |
| `ps` | 실행 중인 프로세스 정보 출력 |
| `jobs` | 백그라운드 작업 목록 출력 |
| `kill` | 프로세스 강제 종료 |
<br>

