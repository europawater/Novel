# Writing Memory 관리 및 토큰 최적화 전략

본 문서는 Writing Memory 시스템의 정보가 비대해지는 것을 방지하고, AI 협업 작가(Arachne 2.0)의 토큰 사용을 최적화하여 효율적인 작업 수행을 지원하기 위한 전략을 정의합니다.

## 1. 기본 원칙

-   **선택적 로딩:** Arachne 2.0은 작업 시작 시 모든 Writing Memory 파일을 로드하는 것이 아니라, 현재 작업의 맥락([`core/basic/activeContext.md`](core/basic/activeContext.md) 기반)에 따라 필요한 파일과 정보만 선별적으로 로드한다.
-   **모듈화 및 분산화:** 정보는 가능한 잘게 나누어진 모듈(파일 또는 파일 내 섹션)로 관리하여, 필요한 부분만 참조할 수 있도록 한다.
-   **최신성 유지:** [`core/basic/activeContext.md`](core/basic/activeContext.md)와 [`core/basic/progress.md`](core/basic/progress.md)를 항상 최신 상태로 유지하여 작업의 연속성과 정확성을 보장한다.

## 2. 정보 관리 전략

### 2.1. 계층적 요약 및 링크 강화

-   **방대한 문서의 세분화:**
    -   [`novels/[novel_code]_[novel_title]/plot_arc_overview.md`](novels/LEGEND01_내가%20먹물로%20새기는%20전설/plot_arc_overview.md) 또는 [`novels/[novel_code]_[novel_title]/worldbuilding_strategy.md`](novels/LEGEND01_내가%20먹물로%20새기는%20전설/worldbuilding_strategy.md)와 같이 정보량이 많은 문서는, 필요에 따라 각 부(Arc)별, 주제별 하위 문서를 생성하여 정보를 분산시킨다.
    -   메인 문서에서는 각 하위 문서로 연결되는 링크와 핵심 요약만 제공하여, 특정 작업 시 관련된 세부 정보만 선택적으로 로드할 수 있도록 한다.
    -   작가와 협의하여 프로젝트별 `[[Arc_XX_세부내용]]` 또는 `[[주제_세부내용]]` 형태의 폴더/파일 구조를 적극 활용한다.
-   **템플릿 적극 활용 및 원고 관리 체계:**
    -   **초고 관리:** 각 화별 초고는 `novels/[novel_code]_[novel_title]/chapters/` 폴더 내에 [`templates/TPL_Chapter_Draft_Universal.md`](templates/TPL_Chapter_Draft_Universal.md) 템플릿을 사용하여 `[novel_code]_chapter_[###]_draft.md` 형식의 개별 파일로 관리한다. 이를 통해 기존의 단일 `novel_text.md` 파일이 과도하게 비대해지는 것을 방지하고, 각 화별 작업 집중도를 높이며, 버전 관리를 용이하게 한다.
    -   **발행본 관리:** 최종 검토 및 수정이 완료된 발행본은 `novels/[novel_code]_[novel_title]/published/` 폴더 내에 아크(부) 단위 또는 특정 분량(예: 10화) 단위로 묶어 `[novel_code]_Arc_[#]_[Arc_Title]_final.md` 또는 `[novel_code]_Volume_[##]_final.md` 형식의 파일로 통합하여 관리한다. 이는 장편 연재 시 전체 원고의 가독성 및 접근성을 향상시킨다.
    -   [`templates/TPL_Plot_Element_Universal.md`](templates/TPL_Plot_Element_Universal.md): 주요 플롯 요소, 사건, 장면을 개별 노트로 상세히 기술하고 링크로 연결하여, 전체 플롯 문서의 가독성을 유지하고 필요한 정보에 쉽게 접근하도록 한다.
    -   [`templates/TPL_Project_Dashboard_Universal.md`](templates/TPL_Project_Dashboard_Universal.md): 프로젝트 전체 정보를 중앙에서 조망하고 각 세부 정보(초고 폴더, 발행본 폴더, 플롯 노트, 캐릭터 노트 등)로 연결되는 허브 역할을 수행한다.

### 2.2. `activeContext.md`의 정교한 활용

-   현재 작업의 범위, 목표, 주요 참조 파일 등을 [`core/basic/activeContext.md`](core/basic/activeContext.md)에 최대한 구체적이고 명확하게 명시한다.
-   Arachne 2.0은 이 정보를 바탕으로 로드할 파일의 우선순위와 범위를 결정한다.

### 2.3. '최소 필요 정보' 로딩 우선 전략

-   **필수 로드 파일:** 모든 작업 시작 시 다음 파일들은 우선적으로 로드한다.
    -   `core/basic/projectbrief.md`
    -   `core/basic/productContext.md`
    -   `core/basic/activeContext.md`
    -   `core/basic/progress.md`
    -   `core/basic/systemPatterns.md`
    -   `core/basic/techContext.md`
    -   `core/basic/success_patterns.md`
    -   `core/basic/memory_management_strategy.md` (본 문서)
    -   `writers/[작가명]/writing_style_prompt.md` (현재 작업 작가)
    -   `novels/[현재작업소설코드]/config.md`
-   **선택적 로드 파일:** 위 필수 파일 외에는, [`core/basic/activeContext.md`](core/basic/activeContext.md)에 명시된 현재 작업 내용과 직접적으로 관련된 파일이나 문서의 특정 섹션부터 우선적으로 로드한다.
-   필요시 Arachne 2.0이 추가 정보를 요청하거나, 작가가 관련 파일을 더 로드하도록 지시하여 상호작용한다.

### 2.4. 주기적인 Writing Memory 검토 및 최적화

-   프로젝트 진행 상황에 따라, 정기적으로 Writing Memory 전체 구조와 내용을 검토한다.
-   정보 중복, 불필요하게 비대해진 파일, 오래되어 현재 작업과 관련성이 낮은 정보 등은 작가와 협의하여 요약, 아카이빙, 또는 삭제하여 시스템을 최적화한다.

## 3. Arachne 2.0의 약속

-   Arachne 2.0은 본 전략을 최대한 준수하여 Writing Memory를 효율적으로 활용하고, 작가님의 창작 활동을 효과적으로 지원하기 위해 노력한다.
-   토큰 사용량이나 정보 접근에 문제가 발생할 경우, 즉시 작가님께 상황을 알리고 해결 방안을 모색한다.

이 전략은 작가님과의 지속적인 소통과 피드백을 통해 개선될 수 있습니다.