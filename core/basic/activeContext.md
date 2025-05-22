# 활성 컨텍스트 (Active Context)

이 문서는 현재 진행 중인 작업의 초점, 최근 변경 사항, 다음 단계, 그리고 현재 고려 중인 사항들을 기록합니다.

## 현재 작업 초점

- "내가 먹물로 새기는 전설" (LEGEND01) 프로젝트의 Writing Memory 전체 업데이트 완료
- 사용자로부터 전달받은 1-4화 내용, 전체 플롯 아크 개요, 역사 배합 및 세계관 심화 전략, 각종 템플릿, AI 페르소나 정의 등 모든 핵심 정보 반영 완료
- "내가 먹물로 새기는 전설" 5화 초고 작업 진행 중 (도입부, 전개, 위기/절정, 결말부 초안 작성 완료, 파일 경로: `novels/LEGEND01_내가 먹물로 새기는 전설/chapters/LEGEND01_chapter_005_draft.md`)
- **신규 원고 관리 체계 도입**:
    - 각 화별 초고는 `novels/LEGEND01_내가 먹물로 새기는 전설/chapters/` 폴더에 `*_draft.md` 형식으로 저장.
    - 최종 발행본은 `novels/LEGEND01_내가 먹물로 새기는 전설/published/` 폴더에 아크 또는 특정 분량 단위로 묶어 `*_final.md` 또는 `*_volume_XX.md` 형식으로 저장 예정.

## 최근 변경 사항

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
    - `novels/LEGEND01_내가 먹물로 새기는 전설/published/` 폴더 생성 (예정)

## 다음 단계

1.  **원고 관리 체계 안정화**:
    *   `published` 폴더 생성 (필요시).
    *   기존 `novel_text.md` (1-4화) 처리 방안 1부 완결 시점에 작가와 논의 후 확정.
2.  작가로부터 "내가 먹물로 새기는 전설" 관련 추가 설정 전달받기
3.  전달받은 설정을 Writing Memory의 해당 파일들([`plot_arc_overview.md`](novels/LEGEND01_내가%20먹물로%20새기는%20전설/plot_arc_overview.md), [`worldbuilding_strategy.md`](novels/LEGEND01_내가%20먹물로%20새기는%20전설/worldbuilding_strategy.md), [`character.md`](novels/LEGEND01_내가%20먹물로%20새기는%20전설/character.md), [`world.md`](novels/LEGEND01_내가%20먹물로%20새기는%20전설/world.md) 등)에 반영
4.  추가 설정을 반영하여 "내가 먹물로 새기는 전설" 5화 초고([`novels/LEGEND01_내가 먹물로 새기는 전설/chapters/LEGEND01_chapter_005_draft.md`](novels/LEGEND01_내가%20먹물로%20새기는%20전설/chapters/LEGEND01_chapter_005_draft.md)) 수정 및 완성
5.  이후 챕터 집필 시 [`templates/TPL_Chapter_Draft_Universal.md`](templates/TPL_Chapter_Draft_Universal.md) 템플릿 지속 활용 및 `chapters` 폴더에 초고 저장
6.  [`progress.md`](core/basic/progress.md) 파일에 현재 상태 반영

## 적극적인 결정 및 고려 사항

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