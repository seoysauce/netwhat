# netwhat

42 본 과정의 네트워크 기초 평가. 코드를 작성하는 프로젝트가 아니라 **객관식 퀴즈** 형태로, 사내 사이트 `netwhat.42.fr`에서 응시하고 결과로 발급되는 암호화 키를 `answer.txt`에 붙여넣어 git으로 제출한다.

> 원본 과제 명세: [`subject.pdf`](./subject.pdf) (영문)

## 과제 개요 / 요구사항

- **형식**: multiple choice quiz (코드 제출 없음)
- **응시 장소**: `netwhat.42.fr` (인트라넷)
- **응시 횟수**: 시도당 1회. 재응시는 프로젝트를 retry 처리해야 가능
- **제출물**: 응시 후 발급되는 encrypted key를 **수정 없이** 그대로 `answer.txt`에 붙여넣어 레포 루트에 푸시
- **평가**: 동료 평가자가 그 키로 정답 검증

## 다룬 주제

subject가 사전 학습으로 명시한 17개 항목:

| 카테고리 | 항목 |
|---|---|
| 주소 체계 | IP 주소 / Netmask / Subnet / Broadcast / 표기법 / Public vs Private / IP 클래스 |
| 전송 계층 | TCP / UDP / Port |
| 네트워크 계층 | OSI 7계층 / 네트워크 계층 모델 |
| 핵심 프로토콜 | DHCP / DNS |
| 라우팅 | 두 장치 간 통신 규칙 / IP 라우팅 / Default gateway |

## 레포 구조

| 파일 | 설명 |
|---|---|
| `answer.txt` | netwhat.42.fr 응시 후 발급된 평가용 토큰 (수정 금지) |
| `subject.pdf` | 원본 과제 명세 |

## 메모

- 코드 과제가 아니므로 **빌드·실행 방법은 해당 없음**.
- `answer.txt`의 토큰은 인트라넷에서 발급된 시점의 응시 결과를 암호화한 것으로, 외부에서 디코딩하거나 검증할 수 없다.
- `subject.pdf`는 [evgenkarlson/ALL_SCHOOL_42 — netwhat](https://github.com/evgenkarlson/ALL_SCHOOL_42/tree/master/00_Projects__(%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D0%BE%D0%B5_%D0%9E%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5)/00_Global_(begin_cadet)/02____netwhat)의 영문 판본.
