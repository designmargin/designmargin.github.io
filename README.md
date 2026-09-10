# designmargin

설계 여유를 계산하는 엔지니어용 웹 계산기 모음.
Engineering calculators for design margin — voltage, current, thermal, timing.

**https://designmargin.github.io/**

## 계산기

| | 주소 | 내용 |
|---|---|---|
| BLDC 최대 회전수 | `/bldc-speed/` | 부하 시 전압 천장에 닿는 회전수. 역기전압 6가지 표기 입력 |
| 전압 분배기 | `/voltage-divider/` | E12·E24·E96 실제 저항 조합 · 부하 · 오차 · 정격 |
| 모터 PI 속도루프 | `/pi-speed-loop/` | 목표 속도 도달·정착 시간. 전류 포화 + 안티와인드업 |

## 만든 방식

- 페이지 하나가 HTML 파일 하나. 외부 라이브러리 없음, 빌드 없음, 서버 없음
- 계산은 전부 브라우저 안에서. 입력값은 어디로도 전송되지 않음
- 라이트·다크 테마, 한국어·영어 병기
- 저장해 두면 오프라인에서도 동작

## 면책

개념 확인과 초기 검토용입니다. 결과를 설계 근거로 그대로 쓰지 마십시오.

For concept checking and early-stage estimation only. Verify against measured
samples before committing to a design.
