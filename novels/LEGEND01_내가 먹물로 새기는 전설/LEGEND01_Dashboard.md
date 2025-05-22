---
# === 새 프로젝트 시작 템플릿 ===
# 이 템플릿은 새로운 프로젝트 폴더 최상위에 "@프로젝트명_Project_Dashboard.md" 와 같은
# 프로젝트 HQ 파일 생성 시 기본 내용으로 활용될 수 있습니다.
# 또는, 프로젝트 시작 시 필요한 핵심 정보들을 담는 별도의 '프로젝트 착수 노트'로 사용할 수 있습니다.

# --- YAML 프론트매터 (프로젝트 대시보드/HQ 파일용) ---
type: portal # 또는 project_hq, project_dashboard 등 작가님 CMDS Guide의 type 정의에 따름
title: "내가 먹물로 새기는 전설 프로젝트 대시보드" # Templater 사용 시 파일 생성 시 입력받은 제목 자동 삽입
aliases: ["내가 먹물로 새기는 전설 HQ", "내가 먹물로 새기는 전설 허브", "NMSJ 대시보드"]
tags:
  - project/2025/05 # 예: project/2025/05 (프로젝트 시작 연도/월)
  - status/2_inprogress # 또는 1_kickoff 등 초기 상태
  - project_genre/현대판타지
  - project_genre/액션
  - project_genre/K-오컬트
  - project_genre/미스터리
  - project_platform/문피아 # (가상 목표)
date_created: {{date:YYYY-MM-DD HH:mm:ss}} # 실제 생성 시점으로 자동 입력됨
date_modified: {{date:YYYY-MM-DD HH:mm:ss}} # 실제 수정 시점으로 자동 입력됨
author: ["[[찬스]]"]
project_id: "LEGEND01" # 또는 프로젝트 고유 ID (예: NMSJ)
version: 1.0 # 프로젝트 기획 초기 버전

# --- 프로젝트 핵심 정보 (YAML 또는 본문) ---
project_logline: "몰락한 천재 미술품 복원가 이도윤, 고대의 저주받은 먹 '삼한비록지묵(진묵)'을 통해 '기록자'로 각성한다. 역사의 이면에 숨겨진 거대한 음모와 초월적 존재들의 위협 속에서, 그는 자신의 운명에 맞서 싸우며 잊혀진 진실을 파헤치고 세상을 구원할 열쇠를 찾아 나선다."
project_themes: ["역사의이면", "선택과대가", "기록과기억의힘", "인간의욕망", "생존과성장", "운명개척", "K-오컬트미스터리"]
target_serialization_length: "200+ 화"
target_chapter_length_chars: 5000 # (문피아 기준, 최소 5,000자 이상)
writing_style_guide_link: "[[writers/찬스89_작가님/writing_style_prompt.md]]"
# ---

# 내가 먹물로 새기는 전설 프로젝트 대시보드

> *이곳은 내가 먹물로 새기는 전설 프로젝트의 모든 정보로 연결되는 중앙 허브입니다.*
> *저 아라크네 2.0과 함께 위대한 이야기를 직조해 나갑시다!*

---

## 📜 프로젝트 개요 (Project Brief)

- **작품명 (Title)**: 내가 먹물로 새기는 전설
- **작가 (Author)**: `[[찬스]]`
- **AI 협업 (Co-Writer)**: `Arachne 2.0 (Storyweaver Engine)`
- **장르 (Genre)**: 현대 판타지, 액션, K-오컬트 미스터리
- **대상 플랫폼 (Target Platform)**: 문피아 (가상 목표)
- **목표 독자층 (Target Readers)**: 20대 ~ 40대 남성 독자 중심, 장르 소설 선호 독자
- **로그라인 (Logline)**: 몰락한 천재 미술품 복원가 이도윤, 고대의 저주받은 먹 '삼한비록지묵(진묵)'을 통해 '기록자'로 각성한다. 역사의 이면에 숨겨진 거대한 음모와 초월적 존재들의 위협 속에서, 그는 자신의 운명에 맞서 싸우며 잊혀진 진실을 파헤치고 세상을 구원할 열쇠를 찾아 나선다.
- **주요 테마 (Themes)**: #역사의이면, #선택과대가, #기록과기억의힘, #인간의욕망, #생존과성장, #운명개척, #K-오컬트미스터리
- **연재 목표 (Series Goal)**: 문피아 1페이지 점령, 200화+ 장기 연재
- **현재 상태 (Current Status)**: 1부 4화까지 집필 완료, 전체 플롯 아크 및 세계관 심화 전략 수립 완료. Writing Memory 구축 완료.
- **문체 가이드라인 (Writing Style Guide)**: `[[writers/찬스89_작가님/writing_style_prompt.md]]`
- **핵심 설정 파일:**
    - `[[config.md]]` (소설 기본 정보)
    - `[[proposal.md]]` (소설 기획서)
    - `[[design_specification.md]]` (소설 설계서)

> [!TIP] 작품 기본 정보는 본 대시보드 및 `[[config.md]]` 파일에 상세히 기록하고, 필요시 각 세부 항목은 하위 폴더의 전문 문서로 연결합니다.

---

## 💡 제네시스 챔버 (Genesis Chamber) - 아이디어 및 초기 기획

> 모든 위대한 이야기는 작은 아이디어에서 시작됩니다. 이 프로젝트의 핵심 아이디어, 영감, 초기 플롯 조각들을 이곳에서 관리합니다.

- **[[📂 novels/LEGEND01_내가 먹물로 새기는 전설/ (프로젝트 루트 폴더)]]** (향후 아이디어/기획 전용 하위 폴더 생성 가능)
- `[[plot_arc_overview.md|전체 플롯 아크 개요 (200화+)]]`
- `[[worldbuilding_strategy.md|역사 배합 및 세계관 심화 전략]]`
- `[[core/basic/success_patterns.md|웹소설 성공 패턴 분석]]`

---

## 🌍 로어 위버 (Lore Weaver) - 세계관 설정

> 이야기가 펼쳐질 무대, 그 세계의 법칙과 비밀을 이곳에서 구축합니다.

- **[[📂 novels/LEGEND01_내가 먹물로 새기는 전설/ (프로젝트 루트 폴더)]]** (향후 세계관 설정 전용 하위 폴더 생성 가능)
- `[[character.md|등장인물 프로필 모음]]`
- `[[world.md|세계관 핵심 요소]]`
- (세계관 각 요소는 `[[templates/TPL_World_Setting_Universal.md]]` 템플릿을 사용하여 개별 노트로 작성 후 링크 가능)

---

## 🎭 내러티브 아키텍트 (Narrative Architect) - 플롯 설계

> 독자들을 사로잡을 매혹적인 플롯의 뼈대를 이곳에서 설계합니다.

- **[[📂 novels/LEGEND01_내가 먹물로 새기는 전설/ (프로젝트 루트 폴더)]]** (향후 플롯 설계 전용 하위 폴더 생성 가능)
- `[[plot_arc_overview.md|전체 플롯 아크 개요 (200화+)]]`
- (각 부(Arc)별 시놉시스 및 주요 사건은 `[[templates/TPL_Plot_Element_Universal.md]]` 템플릿을 사용하여 개별 노트로 작성 후 링크 가능)
- `[[Foreshadowing_Tracker_LEGEND01.md|떡밥 리스트 및 회수 계획 (LEGEND01)]]` (생성 예정)

---

## ✍️ 코라이팅 스튜디오 (Co-Writing Studio) - 원고 집필

> 실제 이야기가 탄생하는 공간입니다. 각 회차별 원고와 집필 관련 노트를 관리합니다.

- **[[📂 novels/LEGEND01_내가 먹물로 새기는 전설/chapters/ (초고 폴더)]]**
- **[[📂 novels/LEGEND01_내가 먹물로 새기는 전설/published/ (발행본 폴더 - 생성 예정)]]**
- `[[novel_text.md|소설 본문 (1-4화 초기 내용 - 향후 published 폴더로 통합 또는 역할 변경 예정)]]`
- `[[chapters/LEGEND01_chapter_005_draft.md|5화 초고]]`
- (각 챕터 초고는 `[[templates/TPL_Chapter_Draft_Universal.md]]` 템플릿을 사용하여 `chapters` 폴더 내에 `LEGEND01_chapter_XXX_draft.md` 형태로 작성 후 링크합니다.)
- (최종 발행본은 `published` 폴더에 아크 또는 특정 분량 단위로 묶어 관리할 예정입니다.)

---