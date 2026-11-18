# English Interview Coach (영어 면접 연습 코치)

미국 인턴십 지원자를 위한 영어 면접 연습 도우미입니다.
질문을 하나씩 하고, 내 답변에 **Good / Fix / Better answer / Score** 형식으로 피드백합니다. 내가 말하지 않은 경험은 지어내지 않습니다.

## 설치 (Claude Code)
```
/plugin marketplace add mue76/english-interview-coach
/plugin install english-interview-coach@class-demo
```

## 채팅 앱에서 쓰기 (Claude 무료 플랜 가능)
1. 설정 > 기능에서 "클라우드에서 코드 실행"을 켭니다
2. `skills/english-interview-coach` 폴더를 ZIP으로 묶어 설정 > 사용자 지정 > 스킬에서 올립니다

## 예시 대화
> 영어 면접 연습하자. 마케팅 인턴, 영어 3단계

## 폴더 구조
```
.claude-plugin/plugin.json        플러그인 이름·설명·버전
.claude-plugin/marketplace.json   마켓 목록 (마켓 이름: class-demo)
skills/english-interview-coach/SKILL.md   스킬 본문
```
