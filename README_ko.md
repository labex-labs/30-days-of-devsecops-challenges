# 30일 DevSecOps 챌린지

## 언어

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![30일 DevSecOps 챌린지](https://course-cover.labex.io/30-days-of-devsecops-challenges.png?lang=ko)](https://labex.io/ko/courses/30-days-of-devsecops-challenges)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ko/courses/30-days-of-devsecops-challenges)

DevSecOps Linux 및 Docker 보안 랩에서 선별한 30일 챌린지 경로로, 호스트 노출 감사부터 권한, 시크릿, 서비스 ID, 컨테이너 보안 강화, Compose 격리, 이미지 위생, 사고 정리까지 진행합니다.

![devops](https://img.shields.io/badge/devops-whitesmoke?style=for-the-badge&logo=devops)
![devsecops](https://img.shields.io/badge/devsecops-whitesmoke?style=for-the-badge&logo=devsecops)


## 연습

|   인덱스 | 이름                           | 난이도   | 연습                                                                                                                                                     |
|-------|------------------------------|-------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
|    01 | 🎯 🆓 리스닝 서비스 감사               | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-audit-listening-services-662167?course=30-days-of-devsecops-challenges'>도전 시작</a>              |
|    02 | 🎯 🆓 불필요한 공용 포트 제거            | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-remove-unnecessary-public-port-662316?course=30-days-of-devsecops-challenges'>도전 시작</a>        |
|    03 | 🎯 🆓 관리자 인터페이스를 로컬호스트로 제한하기   | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-restrict-admin-interface-to-localhost-662317?course=30-days-of-devsecops-challenges'>도전 시작</a> |
|    04 | 🎯 🆓 웹 디렉토리 리스팅 비활성화          | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-disable-web-directory-listing-662309?course=30-days-of-devsecops-challenges'>도전 시작</a>         |
|    05 | 🎯 🆓 노출된 백업 아카이브 제거           | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-remove-exposed-backup-archive-662313?course=30-days-of-devsecops-challenges'>도전 시작</a>         |
|    06 | 🎯 🆓 안전하지 않은 비밀 파일 권한 수정      | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-fix-unsafe-secret-file-permissions-662310?course=30-days-of-devsecops-challenges'>도전 시작</a>    |
|    07 | 🎯 🆓 웹 디렉토리의 전체 쓰기 권한 수정      | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-fix-world-writable-web-directory-662311?course=30-days-of-devsecops-challenges'>도전 시작</a>      |
|    08 | 🎯  전용 서비스 사용자                | 중급    | <a target='_blank' href='https://labex.io/ko/labs/dedicated-service-user-662278?course=30-days-of-devsecops-challenges'>도전 시작</a>                      |
|    09 | 🎯  서비스 환경 파일                 | 중급    | <a target='_blank' href='https://labex.io/ko/labs/service-env-file-662284?course=30-days-of-devsecops-challenges'>도전 시작</a>                            |
|    10 | 🎯  로그 쓰기 경계 설정               | 중급    | <a target='_blank' href='https://labex.io/ko/labs/log-write-boundary-662281?course=30-days-of-devsecops-challenges'>도전 시작</a>                          |
|    11 | 🎯  하드코딩된 자격 증명 제거            | 중급    | <a target='_blank' href='https://labex.io/ko/labs/linux-remove-hardcoded-credentials-662314?course=30-days-of-devsecops-challenges'>도전 시작</a>          |
|    12 | 🎯  프로세스 환경 변수 시크릿 처리         | 중급    | <a target='_blank' href='https://labex.io/ko/labs/process-env-secret-662282?course=30-days-of-devsecops-challenges'>도전 시작</a>                          |
|    13 | 🎯  과도하게 허용된 Sudo 규칙 제거       | 중급    | <a target='_blank' href='https://labex.io/ko/labs/linux-remove-over-permissive-sudo-rule-662315?course=30-days-of-devsecops-challenges'>도전 시작</a>      |
|    14 | 🎯  안전한 스크립트 PATH 설정          | 중급    | <a target='_blank' href='https://labex.io/ko/labs/safe-script-path-662283?course=30-days-of-devsecops-challenges'>도전 시작</a>                            |
|    15 | 🎯  루트 권한 크론 작업 보안 강화         | 중급    | <a target='_blank' href='https://labex.io/ko/labs/linux-harden-root-run-cron-job-662312?course=30-days-of-devsecops-challenges'>도전 시작</a>              |
|    16 | 🎯  Compose Handoff Audit     | 중급    | <a target='_blank' href='https://labex.io/ko/labs/compose-handoff-audit-662564?course=30-days-of-devsecops-challenges'>도전 시작</a>                       |
|    17 | 🎯  Support Portal Audit      | 초급    | <a target='_blank' href='https://labex.io/ko/labs/support-portal-audit-662472?course=30-days-of-devsecops-challenges'>도전 시작</a>                        |
|    18 | 🎯  Metrics Endpoint Exposure | 초급    | <a target='_blank' href='https://labex.io/ko/labs/metrics-endpoint-exposure-662477?course=30-days-of-devsecops-challenges'>도전 시작</a>                   |
|    19 | 🎯  로컬 디버그 콘솔                 | 초급    | <a target='_blank' href='https://labex.io/ko/labs/local-debug-console-662476?course=30-days-of-devsecops-challenges'>도전 시작</a>                         |
|    20 | 🎯  내부 데이터베이스 액세스             | 중급    | <a target='_blank' href='https://labex.io/ko/labs/internal-database-access-662567?course=30-days-of-devsecops-challenges'>도전 시작</a>                    |
|    21 | 🎯  읽기 전용 설정 마운트              | 중급    | <a target='_blank' href='https://labex.io/ko/labs/read-only-config-mount-662479?course=30-days-of-devsecops-challenges'>도전 시작</a>                      |
|    22 | 🎯  Non-Root Image Worker     | 중급    | <a target='_blank' href='https://labex.io/ko/labs/non-root-image-worker-662478?course=30-days-of-devsecops-challenges'>도전 시작</a>                       |
|    23 | 🎯  최소 권한 로그 수집기              | 중급    | <a target='_blank' href='https://labex.io/ko/labs/least-privilege-log-collector-662475?course=30-days-of-devsecops-challenges'>도전 시작</a>               |
|    24 | 🎯  Webhook Docker 소켓         | 중급    | <a target='_blank' href='https://labex.io/ko/labs/webhook-docker-socket-662481?course=30-days-of-devsecops-challenges'>도전 시작</a>                       |
|    25 | 🎯  Compose 시크릿 범위 제한         | 중급    | <a target='_blank' href='https://labex.io/ko/labs/scoped-compose-secret-662569?course=30-days-of-devsecops-challenges'>도전 시작</a>                       |
|    26 | 🎯  서비스 네트워크 분리               | 중급    | <a target='_blank' href='https://labex.io/ko/labs/split-service-networks-662571?course=30-days-of-devsecops-challenges'>도전 시작</a>                      |
|    27 | 🎯  환경 변수의 API 토큰             | 중급    | <a target='_blank' href='https://labex.io/ko/labs/api-token-in-env-662473?course=30-days-of-devsecops-challenges'>도전 시작</a>                            |
|    28 | 🎯  빌드 토큰 유출 해결               | 중급    | <a target='_blank' href='https://labex.io/ko/labs/build-token-leak-662474?course=30-days-of-devsecops-challenges'>도전 시작</a>                            |
|    29 | 🎯  더 안전한 워커 이미지 만들기          | 중급    | <a target='_blank' href='https://labex.io/ko/labs/safer-worker-image-662480?course=30-days-of-devsecops-challenges'>도전 시작</a>                          |
|    30 | 🎯  인시던트 디버그 정리               | 고급    | <a target='_blank' href='https://labex.io/ko/labs/incident-debug-cleanup-662566?course=30-days-of-devsecops-challenges'>도전 시작</a>                      |

## LabEx 소개

[LabEx](https://labex.io) 는 코딩과 기술에 전념하는 대화형 실습 학습 플랫폼입니다. 실험실, AI 지원 및 가상 머신을 결합하여 비디오 없는 실용적인 학습 경험을 제공합니다. 비디오 없는 독점적인 실습 실험실로 엄격한 '실습을 통한 학습' 접근 방식, 브라우저 내 대화형 온라인 환경에서 자동화된 단계별 확인, 스킬 트리 기반 시스템으로 구조화된 콘텐츠 구성, 30 개의 스킬 트리와 6,000 개 이상의 실험실을 포함하는 성장하는 학습 리소스로, [LabEx](https://labex.io) 는 종합적인 실습 교육을 제공합니다. 플랫폼에는 최신 AI 모델을 기반으로 구축된 학습 도우미 Labby 가 포함되어 대화형 학습 경험을 제공합니다.

## 더 보기

- 🔗 [ 프로그래밍 코스](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [ 프로그래밍 프로젝트](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [ 무료 튜토리얼](https://github.com/labex-labs/devops-free-tutorials)

