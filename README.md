# English Interview Coach (영어 면접 연습 코치)

미국 인턴십 지원자를 위한 영어 면접 연습 도우미입니다.
지원 직무와 영어 수준을 먼저 묻고, 질문을 하나씩 합니다. 답할 때마다 **Good / Fix / Better answer / Score** 형식으로 피드백합니다.
내가 말하지 않은 경험이나 숫자는 지어내지 않고 `[ ]` 빈칸으로 남깁니다.

## 설치 — Claude 앱
1. 사용자 지정 > 플러그인 > **추가** > **마켓플레이스 추가**
2. `mue76/english-interview-coach` 입력
3. 목록에서 **english-interview-coach** 설치

파일만 쓰려면: `plugins/english-interview-coach/skills/english-interview-coach/SKILL.md`를 내려받아 **추가** > **플러그인 업로드**로 올립니다.
(설정 > 기능 > "클라우드에서 코드 실행"이 켜져 있어야 합니다)

## 설치 — Claude Code
```
/plugin marketplace add mue76/english-interview-coach
/plugin install english-interview-coach@class-demo
```

## 예시 대화
> 영어 면접 연습하자

## 폴더 구조
```
.claude-plugin/marketplace.json                마켓 목록 (마켓 이름: class-demo)
plugins/english-interview-coach/
  .claude-plugin/plugin.json                   플러그인 이름·설명·버전
  skills/english-interview-coach/SKILL.md      스킬 본문
```
