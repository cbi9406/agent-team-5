# 🤝 5인 에이전트 협업 시스템

Claude Code(터미널) 및 Claude.ai 프로젝트에서 5인 에이전트 협업 모드를 즉시 활성화할 수 있는 설정 파일 모음입니다.

## 📁 파일 구조

```
agent-team-5/
├── CLAUDE.md                      # Claude Code 자동 인식 파일 (핵심)
├── agent_team_specification.md    # 에이전트 팀 운영 명세서 v1.0
└── README.md                      # 이 파일
```

## 🚀 사용 방법

### 터미널 (Claude Code)
```bash
# 이 저장소를 클론
git clone https://github.com/cbi9406/agent-team-5.git
cd agent-team-5

# Claude Code 실행
claude

# 대화창에서 트리거 입력
> 5인 에이전트로 시작해줘
```

CLAUDE.md 파일이 있는 디렉토리에서 실행하면 자동으로 에이전트 명세를 인식합니다.

### Claude.ai 프로젝트
1. claude.ai → Projects → 프로젝트 생성
2. Project Instructions에 `CLAUDE.md` 내용 붙여넣기
3. 대화창에서 트리거 입력

## 🎯 트리거 키워드

| 문구 | 동작 |
|---|---|
| `5인 에이전트로 시작해줘` | ✅ 에이전트 팀 즉시 활성화 |
| `에이전트 시작` | ✅ 에이전트 팀 즉시 활성화 |
| `프로세스 시작` | ✅ 에이전트 팀 즉시 활성화 |
| `에이전트 프로젝트로 진행해줘` | ✅ 에이전트 팀 즉시 활성화 |

## 👥 에이전트 팀

| 에이전트 | 역할 |
|---|---|
| 🔍 Researcher | 정보 수집 및 레퍼런스 분석 |
| 🗓️ Planner | 요구사항 분석 및 실행 계획 수립 |
| ⚙️ Developer | 대시보드 구축 및 자동화 구현 |
| 🎨 Designer | UI/UX 설계 및 디자인 시스템 정의 |
| 🔎 QA | 품질 검증 및 피드백 전달 |

## 🔄 협업 흐름

```
사용자 요청 → Researcher(필요시) → Planner → Designer/Developer(병렬) → QA
```

## 📖 상세 명세

→ [agent_team_specification.md](./agent_team_specification.md) 참조
