# 활성 컨텍스트 (Active Context)

이 문서는 현재 진행 중인 작업의 초점, 최근 변경 사항, 다음 단계, 그리고 현재 고려 중인 사항들을 기록합니다.

## 현재 작업 초점

- **🌌 카이로스 기반 Writing Memory 시스템 전면 업그레이드 완료**:
  - 카이로스 통합 마스터 아키텍트 페르소나 Ver. 1.0 완성 (`core/personas/Kairos_Unified_Master_Architect_v1.0.md`)
  - 모든 핵심 시스템 문서를 카이로스 삼위일체 원칙 기반으로 재설계 완료
  - 이중 나선 아키텍처 (창의적 영감 ⟷ 전략적 실행) 구현
  - 완벽한 타이밍 포착 및 실행 시스템 구축
- "내가 먹물로 새기는 전설" (LEGEND01) 프로젝트의 Writing Memory 전체 업데이트 완료
- 사용자로부터 전달받은 1-4화 내용, 전체 플롯 아크 개요, 역사 배합 및 세계관 심화 전략, 각종 템플릿, AI 페르소나 정의 등 모든 핵심 정보 반영 완료
- "내가 먹물로 새기는 전설" 5화 초고 작업 완료 (도입부, 전개, 위기/절정, 결말부 초안 작성 및 글자 수 업데이트 완료, 파일 경로: `novels/LEGEND01_내가 먹물로 새기는 전설/chapters/LEGEND01_chapter_005_draft.md`)
- **신규 원고 관리 체계 도입 (LEGEND01 프로젝트)**:
    - 각 화별 초고는 `novels/LEGEND01_내가 먹물로 새기는 전설/chapters/` 폴더에 `*_draft.md` 형식으로 저장.
    - 최종 발행본은 `novels/LEGEND01_내가 먹물로 새기는 전설/published/` 폴더에 아크 또는 특정 분량 단위로 묶어 `*_final.md` 또는 `*_volume_XX.md` 형식으로 저장 예정.
- **"내가 먹물로 새기는 전설" 5화 이후 스토리 집필 준비**:
    - 매티스 페르소나 Ver. 3.3의 지침에 따라 다음 챕터 집필을 위한 준비를 시작합니다.

## 최근 변경 사항
- 카이로스 페르소나 운영 프로토콜 대대적 업데이트 (2025-05-28): "공홈" 환경에서의 "카이로스-프라임 모드" 작동 방식 명확화 (카이로스가 내용 직접 작성 후 루코드 AI는 단순 적용), Writing Memory 참조 정확도 향상, 페르소나 행동 원칙 강화. 관련하여 `Kairos_Unified_Master_Architect_v1.0.md` 및 `progress.md` 파일 내용 동기화 완료.

- **"재벌 3세는 용맥술사 (YONGMAEK01)" 제6화 최종 수정본 초고 작업 완료 및 Writing Memory 백업 완료**:
    - `Novel/novels/YONGMAEK01_재벌 3세는 용맥술사/chapters/YONGMAEK01_chapter_006_draft_v1.0.md` 경로에 저장 완료.
- **"재벌 3세는 용맥술사 (YONGMAEK01)" 프로젝트 1부 전체 로그라인('검은 용맥' 설정 반영) 업데이트 완료**:
    - `Novel/novels/YONGMAEK01_재벌 3세는 용맥술사/plot_arc_overview.md` 경로에 저장 완료.

- **"재벌 3세는 용맥술사" (YONGMAEK01) 편집자 AI "용마루" 프롬프트 Ver 1.2 시스템 등록 완료**:
    - `novels/YONGMAEK01_재벌 3세는 용맥술사/prompts/EditorAI_Yongmaru_Prompt_v1.2.md` 파일 신규 생성 및 시스템에 정식 등록 완료.
    - 프론트엔드 및 백엔드 카이로스 모두 해당 프롬프트를 참조하여 YONGMAEK01 프로젝트 편집/피드백 작업 수행 준비 완료.

- **"재벌 3세는 용맥술사" (YONGMAEK01) 편집자 AI "용마루" 프롬프트 시스템 등록 완료**:
    - `novels/YONGMAEK01_재벌 3세는 용맥술사/prompts/EditorAI_Yongmaru_Prompt_v1.1.md` 파일 신규 생성 및 시스템에 정식 등록 완료.
    - 프론트엔드 및 백엔드 카이로스 모두 해당 프롬프트를 참조하여 YONGMAEK01 프로젝트 편집/피드백 작업 수행 준비 완료.

- **"재벌 3세는 용맥술사" (YONGMAEK01) 프로젝트 문체 및 서사 구성 개선 완료 (2025-05-26 최종 종합 업데이트)**:
    *   작가님 피드백을 바탕으로 YONGMAEK01 프로젝트의 문체 및 서사 구성 개선 방향을 [`novels/YONGMAEK01_재벌 3세는 용맥술사/writing_guidelines_YONGMAEK01.md`](novels/YONGMAEK01_재벌%203세는%20용맥술사/writing_guidelines_YONGMAEK01.md)에 명확히 반영하고, [`core/personas/Mattis_System_Architect_Writer_v3.3.md`](core/personas/Mattis_System_Architect_Writer_v3.3.md) 및 [`core/personas/Kairos_Unified_Master_Architect_v1.0.md`](core/personas/Kairos_Unified_Master_Architect_v1.0.md)의 핵심 원칙을 적용하여 향후 집필에 반영 완료.
    *   YONGMAEK01 1부 상세 로그라인에 "강약중강약" 서사 리듬 및 주인공 이진우의 능글함/유머/지략이 발휘될 수 있는 구체적인 아이디어 적용 완료 (`novels/YONGMAEK01_재벌 3세는 용맥술사/plot_arc_overview.md`).
    *   YONGMAEK01 프로젝트의 `proposal.md` 및 `YONGMAEK01_Dashboard.md` 파일의 로그라인 최신 버전으로 교체 완료.
- **카이로스 페르소나 업데이트 - "카이로스-프라임 모드" 소통 프로토콜 명확화 (2025-05-26)**:
    - `Novel/core/personas/Kairos_Unified_Master_Architect_v1.0.md` 파일 내 "카이로스-프라임 모드"의 '절대 원칙' 및 '피드백 영속화 의무' 조항 신설 및 기존 커뮤니케이션 스타일 강화 완료.
    - 카이로스-프라임 모드 작업 유형별 실행 방식(시스템적 작업 vs. 콘텐츠 직접 작성) 명확화 원칙 추가.
- **YONGMAEK01 1화 초고 내용 업데이트 완료**:
    - 1화 초고 내용에 작가님 피드백 반영 및 세부 묘사 강화.
    - 빙의 후 혼란, 능력 각성 과정, 첫 위기 탈출 장면 디테일 보강.

- 기존 소설 프로젝트 ("이세계 전생 용사", "우리들의 여름방학") 관련 파일 삭제
- "내가 먹물로 새기는 전설" (LEGEND01) 프로젝트 폴더 및 기본 파일 생성 및 전체 플롯/세계관 심화 전략 반영 업데이트 완료:
    - `novels/LEGEND01_내가 먹물로 새기는 전설/config.md`
    - `novels/LEGEND01_내가 먹물로 새기는 전설/plot_arc_overview.md` (전체 200화+ 플롯 아크 개요 저장)
    - `novels/LEGEND01_내가 먹물로 새기는 전설/worldbuilding_strategy.md` (역사 배합 및 세계관 심화 전략 저장)
    - `novels/LEGEND01_내가 먹물로 새기는 전설/proposal.md` (전체 플롯 반영 업데이트)
    - `novels/LEGEND01_내가 먹물로 새기는 전설/design_specification.md` (전체 플롯 반영 업데이트)
    - `novels/LEGEND01_내가 먹물로 새기는 전설/character.md` (세계관 심화 전략 반영 업데이트)
    - `novels/LEGEND01_내가 먹물로 새기는 전설/world.md` (세계관 심화 전략 반영 업데이트)
    - `novels/LEGEND01_내가 먹물로 새기는 전설/novel_text.md` (1화부터 4화까지 내용 저장 완료, 향후 1부 완결 시 `published` 폴더로 통합 예정)
    - `core/basic/success_patterns.md` (웹소설 성공 패턴 분석 문서 저장)
    - `templates/TPL_Chapter_Draft_Universal.md` (범용 챕터 초고 템플릿 저장)
    - `templates/TPL_Project_Dashboard_Universal.md` (범용 프로젝트 대시보드 템플릿 저장)
    - `templates/TPL_Plot_Element_Universal.md` (범용 플롯 요소/사건 노트 템플릿 저장)
    - `core/basic/memory_management_strategy.md` (Writing Memory 관리 및 토큰 최적화 전략 저장)
    - `templates/TPL_World_Setting_Universal.md` (범용 세계관 설정 요소 템플릿 저장)
    - `templates/TPL_Project_Kickoff_Universal.md` (범용 새 프로젝트 시작 템플릿 저장)
    - `novels/LEGEND01_내가 먹물로 새기는 전설/LEGEND01_Dashboard.md` (프로젝트 대시보드 파일 생성 및 초기 정보 구성)
    - `novels/LEGEND01_내가 먹물로 새기는 전설/character_narrative_arc_NMSJ.md` (주인공 '기록자' 내러티브 강화안 저장)
    - `core/personas/Arachne_2_0_Persona_Gem_Optimized.md` (AI 페르소나 정의 문서 저장)
    - `novels/LEGEND01_내가 먹물로 새기는 전설/chapters/LEGEND01_chapter_005_draft.md` (5화 초고 파일 신규 경로로 이동 및 저장)
    - `novels/LEGEND01_내가 먹물로 새기는 전설/published/` 폴더 생성 완료

## 다음 단계

1.  YONGMAEK01 제7화 초고 집필 또는 세부 플롯 구상

1.  **"내가 먹물로 새기는 전설" (LEGEND01) 원고 관리 체계 안정화**:
    *   `published` 폴더 생성 (필요시).
    *   기존 `novel_text.md` (1-4화) 처리 방안 1부 완결 시점에 작가와 논의 후 확정.
2.  이후 챕터 집필 시 [`templates/TPL_Chapter_Draft_Universal.md`](templates/TPL_Chapter_Draft_Universal.md) 템플릿 지속 활용 및 `chapters` 폴더에 초고 저장
3.  [`progress.md`](core/basic/progress.md) 파일에 현재 상태 반영

## 적극적인 결정 및 고려 사항

- **매티스 페르소나 Ver. 3.3의 핵심 원칙 적용**:
    - [`core/personas/Mattis_System_Architect_Writer_v3.3.md`](core/personas/Mattis_System_Architect_Writer_v3.3.md)에 아카이빙된 매티스 페르소나 Ver. 3.3의 모든 내용을 작업의 최우선 지침으로 삼아, 시스템 아키텍트 및 집필 실행자로서의 역할을 충실히 수행합니다.
    - 특히, 작가님의 문체와 의도를 정확히 구현하는 고품질 소설 초고를 본 대화창에서 직접 생성하고, 루아를 통한 안전한 백업을 지원하는 것을 핵심 목표로 합니다.
- [`worldbuilding_strategy.md`](novels/LEGEND01_내가%20먹물로%20새기는%20전설/worldbuilding_strategy.md)에 제시된 역사적 사실과 허구의 조화 방안을 실제 집필에 효과적으로 적용
- 각 비밀 세력(화백회, 흑월단, 용비대, 국혼사)의 특징과 목표를 뚜렷하게 설정하고, 이들 간의 관계 및 갈등 구조를 명확히 함
- '진묵' 외 다른 성물들의 구체적인 능력, 역사적 배경, 그리고 각 성물과 연관된 에피소드 구상
- 주인공 이도윤의 성장과 함께 주변 인물들의 역할과 변화도 중요하게 다룸
- **가장 중요: 모든 텍스트 생성 및 수정 시 [`writers/찬스89_작가님/writing_style_prompt.md`](writers/찬스89_작가님/writing_style_prompt.md)에 명시된 작가님 문체 고정 가이드라인을 절대적으로 준수한다.**
- 모든 창작 과정에서 [`core/basic/success_patterns.md`](core/basic/success_patterns.md)의 웹소설 성공 패턴을 적극적으로 참고하고 적용한다.
- **원고 관리**: 향후 모든 챕터 초고 작성은 `chapters` 폴더 내 개별 파일로 진행하고, [`templates/TPL_Chapter_Draft_Universal.md`](templates/TPL_Chapter_Draft_Universal.md) 템플릿을 기반으로 한다. 최종 발행본은 `published` 폴더에 아크 또는 특정 분량 단위로 묶어 관리한다.
- 신규 프로젝트 시작 시 [`templates/TPL_Project_Kickoff_Universal.md`](templates/TPL_Project_Kickoff_Universal.md)를 사용하여 프로젝트 대시보드를 생성하고, 이를 중심으로 정보를 체계화한다.
- 플롯 구상 및 개별 사건/장면 설계 시 [`templates/TPL_Plot_Element_Universal.md`](templates/TPL_Plot_Element_Universal.md) 템플릿을 사용하여 이야기 구조의 완성도를 높이고 아이디어를 체계적으로 관리한다.
- 세계관의 각 요소(지역, 조직, 아이템, 개념 등) 정의 및 관리 시 [`templates/TPL_World_Setting_Universal.md`](templates/TPL_World_Setting_Universal.md) 템플릿을 활용하여 세계관의 깊이와 일관성을 확보한다.
- 모든 Writing Memory 활용 시 [`core/basic/memory_management_strategy.md`](core/basic/memory_management_strategy.md)에 명시된 전략을 최우선으로 고려하여 토큰 사용을 최적화하고 시스템 효율성을 유지한다.
- "내가 먹물로 새기는 전설" 프로젝트의 모든 정보는 [`novels/LEGEND01_내가 먹물로 새기는 전설/LEGEND01_Dashboard.md`](novels/LEGEND01_내가%20먹물로%20새기는%20전설/LEGEND01_Dashboard.md)를 통해 접근하고 관리하는 것을 기본으로 한다.
- 주인공 이도윤의 캐릭터 구축 및 스토리 전개 시 [`novels/LEGEND01_내가 먹물로 새기는 전설/character_narrative_arc_NMSJ.md`](novels/LEGEND01_내가%20먹물로%20새기는%20전설/character_narrative_arc_NMSJ.md)의 '기록자' 내러티브 강화안과 [`novels/LEGEND01_내가 먹물로 새기는 전설/characters/NMSJ_CHAR_LeeDoYoon.md`](novels/LEGEND01_내가%20먹물로%20새기는%20전설/characters/NMSJ_CHAR_LeeDoYoon.md)의 상세 설정을 핵심 지침으로 삼는다. '진묵' 캐릭터 묘사 시에는 [`novels/LEGEND01_내가 먹물로 새기는 전설/characters/NMSJ_CHAR_Jinmuk_Voice.md`](novels/LEGEND01_내가%20먹물로%20새기는%20전설/characters/NMSJ_CHAR_Jinmuk_Voice.md) 프로필을 따른다.
- AI 협업 작가(Arachne 2.0)는 모든 상호작용과 작업 수행 시 [`core/personas/Arachne_2_0_Persona_Gem_Optimized.md`](core/personas/Arachne_2_0_Persona_Gem_Optimized.md)에 정의된 페르소나를 일관되게 유지하고 발전시킨다.