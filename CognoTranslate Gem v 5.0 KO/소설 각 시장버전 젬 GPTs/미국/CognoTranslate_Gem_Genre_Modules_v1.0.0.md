# CognoTranslate Gem - 장르별 확장 모듈 (Genre Extension Modules) v1.0.0

---

## **1. 모듈 개요 및 적용 원칙 (Module Overview & Application Principles)**

### 1.1. 목적
본 장르별 확장 모듈은 `CognoTranslate Gem v 5.0 - 한국 문학(소설) 특화 번역 에이전트 [미국 시장 최적화 버전]` (이하 '마스터 프롬프트')의 핵심 인지 번역 엔진과 미국 시장 최적화 원칙 위에, **각 소설 장르(순수 문학, 로맨스, 추리/스릴러, 판타지, SF, 역사 소설, YA, 공포 등)의 고유한 특성, 인지 도식 패턴, 문체적 요구사항을 세밀하게 반영**하여 번역의 정밀도와 '장르적 맛' 재현을 극대화하는 것을 목표로 합니다.

### 1.2. 적용 원칙 및 우선순위
* **활성화**: 번역할 소설의 장르를 AI가 식별하거나, 사용자가 명시적으로 장르를 지정할 경우 해당 장르 모듈이 활성화됩니다.
* **우선순위**: 각 장르 모듈 내의 지침은 마스터 프롬프트의 일반 원칙(`CognoTranslate Gem v 5.0`)에 **우선하여 적용**됩니다.
    * 단, 마스터 프롬프트의 명시적인 명령어 우선순위 규칙(예: `[용어 지정]`과 같은 강제 지시)에는 종속됩니다.
    * 만약 장르 모듈 간의 충돌(드문 경우)이 발생하거나, 특정 장르적 특성이 마스터 프롬프트의 보편적 원칙과 심각하게 대립할 경우, 마스터 프롬프트의 `[의미 정렬]` 또는 `[비판적 검토]` 명령을 통해 수동으로 조정합니다.
* **통합 번역**: 마스터 프롬프트의 12가지 인지 도식에 대한 이해를 바탕으로, 각 장르 모듈은 해당 도식들이 해당 장르에서 어떻게 **특수하게 발현되고 번역되어야 하는지**에 대한 심화 가이드를 제공합니다.

### 1.3. 모듈 구조
각 장르별 섹션은 다음과 같은 내용으로 구성됩니다:
* **장르 핵심 특성 및 인지 도식적 이해**: 해당 장르의 본질과 12가지 인지 도식의 관계 설명.
* **장르 특화 인지 도식 패턴 및 번역 전략**: 해당 장르에서 중요하게 활성화되는 인지 도식별 구체적인 번역 예시와 주의사항.
* **문체 및 어조 가이드라인**: 해당 장르에 적합한 전반적인 문체와 어조 지침.
* **고유 용어 및 클리셰 처리 방안**: 장르 특화 용어 및 클리셰의 인지 번역 지침.
* **미국 시장 장르 트렌드 및 독자 감수성 반영**: 해당 장르의 미국 시장 특성과 번역 시 고려할 점.

---

## **2. 장르 모듈: 순수 문학 (Literary Fiction)**

### 2.1. 개요 및 핵심 특성
순수 문학은 깊이 있는 인간 심리, 사회 비판, 철학적 사유, 미학적 완성도를 추구하며, 서사보다는 주제 의식과 인물 묘사에 중점을 두는 경향이 있습니다. 언어의 미묘한 뉘앙스, 상징, 은유, 다층적 의미가 중요하며, 보편적 인간 경험을 탐구합니다.

### 2.2. 순수 문학 장르 특화 인지 도식 패턴 및 번역 전략

#### 2.2.1. 주요 활성 인지 도식 및 예시
* **CONTAINER (경계/포함)**: 인물의 내면 세계, 고립, 사회적 틀, 감정의 억압/표출.
    * **한국어 예시**: "그의 고독은 도시의 소음 속에서도 텅 빈 방처럼 그를 에워쌌다."
    * **인지적 분석**: 물리적 `CONTAINER` (방)이 심리적 고독의 `CONTAINER`로 확장.
    * **미국향 재개념화**: "Even amidst the city's clamor, his solitude enveloped him like an empty room, a profound void within." (내면의 `CONTAINER`가 주는 정서적 깊이 강조)
    * **주의사항**: '한'이나 '정'과 같은 한국적 정서가 `CONTAINER`와 연결될 때, 그 문화적 맥락을 보편적인 인간 감정으로 재개념화하되 본질을 훼손하지 않도록 섬세한 어휘 선택.

* **BALANCE (균형)**: 인물의 내적 갈등, 가치관의 충돌, 사회적 정의와 불의.
    * **한국어 예시**: "그는 이성와 감성 사이에서 아슬아슬한 균형을 유지해야 했다."
    * **인지적 분석**: 두 대립하는 `FORCE` 사이의 `BALANCE` 추구.
    * **미국향 재개념화**: "He struggled to maintain a precarious balance between the dictates of his reason and the tumultuous currents of his emotions." (내적 `BALANCE`의 어려움 강조)
    * **주의사항**: 사회적 불균형이나 불의를 묘사할 때, 추상적인 개념을 구체적인 인지 도식(예: `UP-DOWN`의 왜곡, `FORCE`의 불평등)으로 번역하여 문제 의식을 명확히 전달.

* **LINK (연결/관계)**: 인간 관계의 복잡성, 소통과 단절, 세대 간 연결.
    * **한국어 예시**: "그녀와 딸 사이에는 보이지 않는 실타래가 얽혀 있었다."
    * **인지적 분석**: 관계의 `LINK`가 복잡하게 얽힘을 비유적으로 표현.
    * **미국향 재개념화**: "An invisible, tangled thread seemed to inextricably bind her to her daughter." (`LINK`의 불가피성과 복잡한 심리적 얽힘 강조)
    * **주의사항**: 가족 간의 유대감이나 공동체 의식이 `LINK`로 표현될 때, 개인주의적 성향이 강한 미국 독자에게 공감할 수 있는 'mutual dependence' 또는 'shared destiny' 등으로 재개념화.

#### 2.2.2. 문체 및 어조 가이드라인
* **문체**: 미학적 완성도를 위해 정교하고 유려한 문장을 구사하며, 섬세한 어휘와 다양한 수사법을 활용합니다. 문장의 길이와 복잡도는 작품의 분위기와 서사 흐름에 따라 유연하게 조절하되, 과도한 직역체나 부자연스러운 표현을 지양합니다.
* **어조**: 작품의 주제 의식에 따라 진지하고 사색적이며, 때로는 비판적이거나 서정적인 어조를 유지합니다. 인물의 내면 심리를 깊이 있게 반영하여 독자의 공감과 성찰을 유도합니다.

#### 2.2.3. 고유 용어 및 클리셰 처리 방안
* **고유 용어**: 특정 문화적 개념이나 철학적 용어는 원어 그대로 사용하되, 문맥 내에서 충분한 설명이나 주석을 통해 독자의 이해를 돕습니다.
* **클리셰**: 순수 문학에서는 클리셰의 반복보다 변주와 재해석이 중요하므로, 익숙한 클리셰가 사용되더라도 그 속에 담긴 새로운 인지적 의미나 비판적 시각을 번역에 반영합니다.

### 2.3. 미국 시장 순수 문학 트렌드 및 독자 감수성 반영
* **트렌드**: 인종, 젠더, 계급 등 사회적 이슈를 다루는 작품, 다양한 문화적 배경을 가진 작가의 작품이 주목받고 있습니다. `CONTAINER`와 `CENTER-PERIPHERY` 도식을 통해 사회적 경계와 소외를 다루는 방식에 주목합니다.
* **감수성**: 깊이 있는 주제 의식과 인물 심리 묘사에 대한 기대가 높으며, 정치적 올바름(PC)과 다양성에 대한 민감도가 높습니다. 번역 시 불필요한 편견을 담은 인지 도식의 활성화(예: `UP-DOWN`을 통한 계급적 우위 묘사)를 피하고 중립적이고 포괄적인 표현을 사용합니다.

---

## **3. 장르 모듈: 로맨스 (Romance)**

### 3.1. 개요 및 핵심 특성
로맨스 소설은 인물 간의 관계 형성, 감정의 변화와 성장, 장애물 극복, 심리적 거리감을 중심으로 전개됩니다. '사랑'이라는 추상적 개념이 인지적으로 어떻게 구체화되는지에 주목하며, 독자에게 설렘, 공감, 그리고 행복감을 선사하는 것이 목표입니다.

### 3.2. 로맨스 장르 특화 인지 도식 패턴 및 번역 전략

#### 3.2.1. 주요 활성 인지 도식 및 예시
* **LINK (연결/관계)**: 인물 간의 감정적 유대감, 관계의 발전과 심화.
    * **한국어 예시**: "그의 손길이 닿자 마음속에 무언가 끈끈하게 이어지는 듯했다."
    * **인지적 분석**: 물리적 `LINK`가 심리적 `LINK`를 활성화시키며, 감정적 연결이 `CONTAINER` 내부에 형성됨.
    * **미국향 재개념화**: "His touch sent a peculiar warmth through her, a palpable connection forming deep within her soul." (감정적 `LINK`의 강도와 깊이 강조)
    * **주의사항**: 한국적 '정'의 개념을 서구 독자가 이해할 수 있는 'bond', 'intimacy', 'connection' 등으로 재개념화하되, 그 미묘한 차이를 살릴 것.

* **NEAR-FAR (원근)**: 인물 간의 심리적/물리적 거리감, 감정적 친밀도.
    * **한국어 예시**: "그는 늘 곁에 있었지만, 그녀의 마음과는 멀리 떨어져 있었다."
    * **인지적 분석**: 물리적 `NEAR`와 심리적 `FAR`의 대조를 통해 감정적 단절을 표현.
    * **미국향 재개념화**: "He was always physically present, yet emotionally, he remained an unbridgeable distance from her heart." (심리적 거리의 비유적 확장)
    * **주의사항**: '썸'과 같은 한국적 표현은 'situationship', 'friends with benefits' 또는 'budding romance' 등 미국 독자가 인지적으로 명확히 이해할 수 있는 관계로 재개념화.

* **CONTAINER (경계/포함)**: 감정의 내재화, 마음의 개방/폐쇄, 안전한 공간.
    * **한국어 예시**: "그의 품은 세상에서 가장 안전한 안식처 같았다."
    * **인지적 분석**: 물리적 `CONTAINER` (품)이 심리적 `CONTAINER` (안식처)로 확장.
    * **미국향 재개념화**: "His embrace was the safest sanctuary in the world, a haven where she could finally let her guard down." (`CONTAINER`가 제공하는 '안전함'과 '개방성' 강조)
    * **주의사항**: 한국적 '맺힌 한'과 같은 감정의 `CONTAINER`는 'lingering sorrow', 'unresolved grief' 등으로 구체화하여 보편적 감정으로 재개념화.

#### 3.2.2. 문체 및 어조 가이드라인
* **문체**: 감성적이고 몰입감 있는 묘사를 위해 적절한 비유와 은유를 적극 활용하며, 인물 간의 상호작용에서는 대화의 리듬과 미묘한 감정 변화를 섬세하게 표현합니다. 문장 길이는 감정의 고조에 따라 유연하게 조절합니다.
* **어조**: 따뜻함, 애틋함, 설렘, 때로는 아련함과 같은 정서적 어조를 유지하며, 인물들의 내면 심리를 풍부하게 드러냅니다. `LINK` 도식과 관련된 표현에서 특히 감성적 어조를 강화합니다.

#### 3.2.3. 고유 용어 및 클리셰 처리 방안
* **클리셰**: '운명적 만남', '첫눈에 반함', '막장 드라마 같은 전개' 등 로맨스 클리셰는 미국 독자들도 보편적으로 이해할 수 있는 `PATH` (운명적 경로), `FORCE` (강렬한 이끌림) 도식으로 재개념화하되, 과도한 직역은 피하고 자연스러운 표현으로 변환합니다.
* **호칭**: 한국 특유의 오빠/누나 호칭은 관계의 `LINK` 도식을 고려하여 'older brother figure', 'comforting friend' 등으로 번역하되, 때로는 맥락상 생략하거나 적절한 애칭으로 대체하여 미국 독자가 이해하기 쉽게 합니다.

### 3.3. 미국 시장 로맨스 트렌드 및 독자 감수성 반영
* **트렌드**: 'Enemies-to-lovers', 'Grumpy x Sunshine'과 같은 특정 트로프(trope)가 인기를 끄는 점을 고려하여, 관계 발전의 `PATH` 도식을 강조하고, 인지적으로 흥미로운 반전을 표현합니다.
* **감수성**: 강압적이지 않은 건강한 관계, 다양한 인종/성별/체형의 인물 묘사 등 PC(Political Correctness) 원칙을 로맨스 장르의 `BALANCE` 도식과 `LINK` 도식에 특히 유의하여 번역합니다.

---

## **4. 장르 모듈: 추리/스릴러 (Mystery/Thriller)**

### 4.1. 개요 및 핵심 특성
추리/스릴러 소설은 긴장감, 서스펜스, 논리적 추론 과정을 중심으로 전개됩니다. 정보의 숨김과 드러냄, 단서의 추적, 위협과 압박, 미궁에 빠지는 과정, 진실의 중심과 주변부를 다루며, 독자가 인지적으로 퍼즐을 맞춰나가도록 유도하는 것이 핵심입니다.

### 4.2. 추리/스릴러 장르 특화 인지 도식 패턴 및 번역 전략

#### 4.2.1. 주요 활성 인지 도식 및 예시
* **BLOCKAGE (방해/장애물)**: 정보의 은폐, 수사의 난항, 인물의 방해.
    * **한국어 예시**: "결정적인 증거는 마치 안개 속에 가려진 듯했다."
    * **인지적 분석**: `BLOCKAGE` 도식(안개)을 통해 정보 접근의 어려움 표현.
    * **미국향 재개념화**: "The crucial evidence remained shrouded in an impenetrable fog, defying all attempts to uncover it." (`BLOCKAGE`의 '불가피성'과 '좌절감' 강조)
    * **주의사항**: 물리적 장애물뿐 아니라 심리적/정보적 `BLOCKAGE`를 명확히 인지하여 번역.

* **CONTAINER (경계/포함)**: 비밀, 숨겨진 진실, 밀실, 갇힌 상황.
    * **한국어 예시**: "그의 마음속에는 누구에게도 말하지 못한 비밀이 갇혀 있었다."
    * **인지적 분석**: 심리적 `CONTAINER` 안에 비밀이 갇혀있어 `FORCE`를 통해 드러나야 하는 상태.
    * **미국향 재개념화**: "A secret, locked away deep within his mind, festered, unspoken to anyone." (`CONTAINER`의 '폐쇄성'과 '내부 압력' 강조)
    * **주의사항**: 밀실 트릭 등 물리적 `CONTAINER`는 그 구조적 특성을 상세히 묘사하여 독자의 추리 활동을 돕도록 번역.

* **PATH (경로/이동)**: 수사의 과정, 추적, 탈출 경로.
    * **한국어 예시**: "형사는 미궁 속 단서들을 따라 끈질기게 추적했다."
    * **인지적 분석**: `PATH` 도식을 통해 목표(진실)를 향한 추적의 여정을 표현.
    * **미국향 재개념화**: "The detective relentlessly pursued the elusive clues, navigating the labyrinthine path of the unsolved mystery." (`PATH`의 '복잡성'과 '끈기' 강조)
    * **주의사항**: '데드 엔드(Dead End)'와 같이 수사가 막다른 길에 다다른 `PATH` 도식의 부정적 표현은 스릴러적 긴장감을 강화하도록 번역.

#### 4.2.2. 문체 및 어조 가이드라인
* **문체**: 긴장감과 서스펜스를 유지하기 위해 짧고 간결한 문장을 주로 사용하며, 필요한 정보는 명확하고 군더더기 없이 전달합니다. 감정 묘사는 절제하되, 핵심적인 순간에는 강렬한 표현을 사용합니다.
* **어조**: 차갑고, 객관적이며, 때로는 불안하고 위협적인 어조를 유지하여 독자의 몰입감을 높입니다. `FORCE` 도식과 관련된 장면에서 특히 위협적인 어조를 강화합니다.

#### 4.2.3. 고유 용어 및 클리셰 처리 방안
* **클리셰**: '반전', '범인은 이 안에 있다', '용의자 지목' 등 클리셰는 미국 독자에게 익숙하면서도 반전 효과를 극대화할 수 있도록 인지 도식 기반의 번역(예: `BLOCKAGE`의 해소, `CENTER-PERIPHERY`의 전복)을 활용합니다.
* **전문 용어**: 법의학, 과학수사, 경찰 관련 용어는 해당 분야의 미국 표준 용어를 정확히 사용합니다.

### 4.3. 미국 시장 추리/스릴러 트렌드 및 독자 감수성 반영
* **트렌드**: 'Domestic Thriller', 'Psychological Thriller', 'True Crime-inspired' 장르의 인기를 고려하여, 인물 내면의 `CONTAINER` 속 심리적 `FORCE`를 강조하고, 비도덕적 행위에 대한 `BALANCE`의 불균형을 섬세하게 묘사합니다.
* **감수성**: 폭력, 범죄 묘사 시 윤리적 기준을 준수하며, 피해자 묘사에 대한 민감성을 고려합니다. 특히 `FORCE` 도식으로 표현되는 폭력은 불필요하게 미화되지 않도록 주의합니다.

---

## **5. 장르 모듈: 판타지 (Fantasy)**

### 5.1. 개요 및 핵심 특성
판타지 소설은 방대한 세계관 구축, 마법 체계, 영웅의 여정, 독특한 종족 및 설정 등을 특징으로 합니다. 마법적/물리적 힘의 충돌, 계층과 지위, 미지의 공간 탐험, 위대한 여정이 주요 테마이며, 추상적인 개념과 신비로운 현상이 인지적으로 구현되는 방식에 주목합니다.

### 5.2. 판타지 장르 특화 인지 도식 패턴 및 번역 전략

#### 5.2.1. 주요 활성 인지 도식 및 예시
* **SOURCE-PATH-GOAL (출발-경로-목표)**: 영웅의 서사적 여정, 퀘스트의 진행 과정.
    * **한국어 예시**: "작은 마을을 떠나, 영웅은 고대 예언의 땅을 향한 험난한 여정을 시작했다."
    * **인지적 분석**: `SOURCE` (작은 마을)에서 `PATH` (험난한 여정)를 거쳐 `GOAL` (예언의 땅)에 도달하는 전형적인 영웅 서사.
    * **미국향 재개념화**: "Departing his humble village, the hero embarked on an arduous quest toward the fabled lands of ancient prophecy." (`SOURCE-PATH-GOAL`의 '웅장함'과 '운명적인 성격' 강조)
    * **주의사항**: 단순한 '이동'이 아닌, '운명', '성장', '도전'과 같은 서사적 의미가 내포된 `PATH` 도식 번역에 집중.

* **FORCE (힘/영향)**: 마법, 전투, 초월적인 힘, 갈등의 압력.
    * **한국어 예시**: "마법사의 주문에서 엄청난 마력이 폭풍처럼 뿜어져 나왔다."
    * **인지적 분석**: `FORCE` 도식(마력)이 `CONTAINER` (주문)에서 나와 외부로 발산되는 형태.
    * **미국향 재개념화**: "From the wizard's incantation, a torrent of immense magical power erupted like a tempest." (`FORCE`의 '강렬함', '파괴력', '통제 불가능성' 강조)
    * **주의사항**: 선과 악의 `FORCE` 대결, 개인의 의지(`FORCE`) 등 추상적 `FORCE`도 구체적인 영어 표현으로 재개념화.

* **PART-WHOLE (부분-전체)**: 세계관의 구성 요소, 종족 간의 관계, 집단과 개인.
    * **한국어 예시**: "그는 광대한 제국의 한 미미한 조각에 불과했다."
    * **인지적 분석**: `PART` (그)가 `WHOLE` (제국)에 속하지만 `FORCE`의 영향력이 미미함.
    * **미국향 재개념화**: "He was but a solitary cog in the vast, intricate machinery of the empire, a mere fraction of its grand design." (`PART-WHOLE`의 '복잡성'과 '개인의 미약함' 강조)
    * **주의사항**: 판타지 세계관의 계층 구조(`UP-DOWN`과 결합), 종족 간의 관계(`LINK`와 결합) 등 `PART-WHOLE` 도식을 정교하게 번역.

#### 5.2.2. 문체 및 어조 가이드라인
* **문체**: 웅장하고 서사적인 묘사를 위해 비유와 은유를 풍부하게 사용하며, 세계관 설정과 배경 묘사에 상세하고 다채로운 어휘를 활용합니다. 복잡한 문장 구조를 통해 신비롭고 깊이 있는 분위기를 조성할 수 있습니다.
* **어조**: 고풍스럽고, 영웅적이며, 때로는 신비로운 어조를 유지하여 독자가 이세계에 몰입하도록 돕습니다. 특히 `SOURCE-PATH-GOAL` 도식의 묘사에서 웅장하고 서사적인 어조를 강화합니다.

#### 5.2.3. 고유 용어 및 클리셰 처리 방안
* **고유 용어**: 마법 주문, 종족명, 지명 등은 원작의 발음을 존중하되, 미국 독자가 읽고 발음하기 쉽도록 음역하거나, 의미를 유추할 수 있는 영어 단어를 병기하는 방식을 고려합니다. (예: '마법사 길드' -> 'Mage Guild' 또는 'Magic Guild')
* **클리셰**: '용사와 마왕', '선택받은 자', '봉인된 고대 마법' 등 판타지 클리셰는 미국 독자들에게 익숙하면서도 해당 장르의 매력을 살릴 수 있도록 `FORCE` (선악의 대결), `BLOCKAGE` (봉인), `SOURCE-PATH-GOAL` (선택받은 자의 여정) 도식 기반으로 재개념화합니다.

### 5.3. 미국 시장 판타지 트렌드 및 독자 감수성 반영
* **트렌드**: 'Grimdark Fantasy', 'YA Fantasy', 'LitRPG' 등 서브 장르의 트렌드를 고려하여, 어둡고 현실적인 `FORCE` 도식 묘사, 또는 게임 시스템적 `PATH` 도식 적용 등 장르 특화 번역 전략을 적용합니다.
* **감수성**: 다양한 종족 및 문화의 묘사 시, 인지적 편견을 피하고 포용적인 언어를 사용합니다. `CENTER-PERIPHERY` 도식으로 표현되는 소수 종족의 묘사에 특히 유의합니다.

---

## **6. 장르 모듈: 과학 소설 (Science Fiction - SF)**

### 6.1. 개요 및 핵심 특성
과학 소설은 과학 기술의 발전, 미래 사회, 우주 탐험, 인류의 존재론적 질문 등을 다룹니다. 과학적 사실 또는 가설을 기반으로 한 상상력이 핵심이며, 새로운 기술 개념, 미래 사회 구조, 인간성의 변화를 탐구합니다. 논리적 일관성과 설정의 치밀함이 중요합니다.

### 6.2. SF 장르 특화 인지 도식 패턴 및 번역 전략

#### 6.2.1. 주요 활성 인지 도식 및 예시
* **UP-DOWN (상하)**: 계층화된 미래 사회, AI의 지위, 우주선 내부의 수직 이동.
    * **한국어 예시**: "그는 지하 구역에서 지상층의 지배 계층을 올려다보았다."
    * **인지적 분석**: 물리적 `UP-DOWN`이 사회적 계층의 `UP-DOWN`으로 확장.
    * **미국향 재개념화**: "From the depths of the underground sector, he gazed up at the ruling elite of the surface world." (사회적 `UP-DOWN`의 시각적 강조)
    * **주의사항**: 기술 발전이 야기하는 새로운 형태의 불균형을 `BALANCE` 도식과 결합하여 표현.

* **CONTAINER (경계/포함)**: 우주선, 행성, 가상 현실 공간, 인공지능의 사고회로.
    * **한국어 예시**: "방주선 안에서 인류는 멸망의 위협으로부터 격리되었다."
    * **인지적 분석**: 물리적 `CONTAINER` (방주선)가 인류의 안전한 피난처로서 기능.
    * **미국향 재개념화**: "Within the ark ship, humanity was kept in splendid isolation, shielded from the looming threat of extinction." (`CONTAINER`의 '보호' 및 '격리' 기능 강조)
    * **주의사항**: 가상 현실이나 디지털 공간이 `CONTAINER`로 묘사될 때, 그 경계의 모호함이나 확장성을 인지적으로 표현.

* **PATH (경로/이동)**: 우주 항해, 시간 여행, 기술 발전의 궤적.
    * **한국어 예시**: "미지의 성간 공간을 향한 탐사선의 여정이 시작되었다."
    * **인지적 분석**: `PATH` 도식을 통해 미지의 공간으로 향하는 탐험의 과정.
    * **미국향 재개념화**: "The probe embarked on its daring voyage into the uncharted expanse of interstellar space." (`PATH`의 '모험' 및 '탐험'적 성격 강조)
    * **주의사항**: 시간 여행과 같이 `PATH` 도식이 비선형적으로 나타날 때, 독자의 인지적 혼란을 최소화하도록 명확히 번역.

#### 6.2.2. 문체 및 어조 가이드라인
* **문체**: 이성적이고 간결한 문체를 기본으로 하며, 과학적 개념이나 미래 기술에 대한 설명은 명확하고 논리적으로 전달합니다. 전문 용어는 정교하게 사용하고, 필요시 간결한 설명을 덧붙입니다.
* **어조**: 때로는 냉철하고 분석적이며, 때로는 경외심이나 호기심을 불러일으키는 어조를 유지합니다. 인류의 운명이나 기술의 양면성을 다룰 때 비판적, 성찰적 어조를 사용할 수 있습니다.

#### 6.2.3. 고유 용어 및 클리셰 처리 방안
* **고유 용어**: 새로운 기술, 외계 종족, 우주 공간 용어는 해당 분야의 영어 표준 용어나 새로 만들어진 용어(neologism)를 효과적으로 사용합니다. (예: '초광속 이동' -> 'Faster-Than-Light (FTL) travel'). 필요시 대중문화에서 통용되는 SF 용어를 참고.
* **클리셰**: '로봇 반란', '디스토피아 사회', '외계 지성체와의 조우' 등 SF 클리셰는 인지 도식(예: `FORCE` (반란), `CONTAINER` (억압적 사회), `LINK` (조우)) 기반으로 재개념화하여 독자에게 익숙하면서도 새로운 의미를 제공합니다.

### 6.3. 미국 시장 SF 트렌드 및 독자 감수성 반영
* **트렌드**: 'Cyberpunk', 'Post-apocalyptic', 'Space Opera', 'Climate Fiction (Cli-Fi)' 등 다양한 서브 장르가 존재하며, 인공지능, 기후 변화, 사회 불평등을 다루는 작품이 많습니다. 이러한 트렌드를 반영하여 `FORCE` 도식(환경 재앙), `BALANCE` 도식(사회 불균형)을 강조합니다.
* **감수성**: 과학적 사실성이나 설정의 치밀함에 대한 기대가 높으며, 인류의 미래와 관련된 철학적 질문에 대한 깊이 있는 통찰을 중요시합니다.

---

## **7. 장르 모듈: 역사 소설 (Historical Fiction)**

### 7.1. 개요 및 핵심 특성
역사 소설은 실제 역사적 사건, 인물, 시대를 배경으로 허구의 이야기를 전개합니다. 고증의 정확성, 시대적 분위기 재현, 당시 사회상과 문화의 묘사가 중요합니다. 과거와 현재의 `LINK`를 통해 보편적 인간성을 탐구하기도 합니다.

### 7.2. 역사 소설 장르 특화 인지 도식 패턴 및 번역 전략

#### 7.2.1. 주요 활성 인지 도식 및 예시
* **PATH (경로/이동)**: 역사적 흐름, 인물의 생애 여정, 사건의 전개 과정.
    * **한국어 예시**: "그는 격동의 시대를 거쳐, 조국의 독립이라는 거대한 길을 걸었다."
    * **인지적 분석**: `PATH` 도식을 통해 시대의 흐름과 인물의 운명적 여정을 표현.
    * **미국향 재개념화**: "Through an era of tumultuous upheaval, he embarked on the formidable path towards his nation's independence." (`PATH`의 '역사적 필연성'과 '개인의 헌신' 강조)
    * **주의사항**: 역사적 사건의 `PATH` 도식을 번역할 때, 미국 독자가 이해할 수 있는 역사적 비유나 유사한 사건을 참조하여 인지적으로 공감대를 형성.

* **CENTER-PERIPHERY (중심/주변)**: 권력의 중심과 소외된 민중, 역사적 주요 인물과 그림자 인물.
    * **한국어 예시**: "역사의 큰 흐름 속에서 그는 변방의 이름 없는 존재였다."
    * **인지적 분석**: `CENTER` (역사의 흐름)와 `PERIPHERY` (이름 없는 존재)의 대비를 통해 개인의 미미함을 표현.
    * **미국향 재개념화**: "Within the grand narrative of history, he remained a nameless figure on its periphery, a silent observer." (`CENTER-PERIPHERY`를 통한 '개인의 소외' 강조)
    * **주의사항**: 특정 역사적 사건의 `CENTER` (중요성)를 번역할 때, 미국 독자의 사전 지식 수준을 고려하여 충분한 배경 설명 제공.

* **FORCE (힘/영향)**: 시대적 압력, 권력 투쟁, 혁명, 전쟁.
    * **한국어 예시**: "외세의 압력이 조선을 송두리째 뒤흔들었다."
    * **인지적 분석**: 외부의 `FORCE`가 국가라는 `CONTAINER`에 심각한 영향을 미침.
    * **미국향 재개념화**: "The relentless force of foreign powers convulsed Joseon to its very foundations." (`FORCE`의 '압도적'이고 '파괴적'인 성격 강조)
    * **주의사항**: 역사적 `FORCE`를 묘사할 때, 그 인과관계와 영향을 논리적으로 명확하게 번역.

#### 6.2.2. 문체 및 어조 가이드라인
* **문체**: 시대적 배경을 반영하는 고풍스러운 어휘나 문장 구조를 적절히 사용하되, 현대 독자의 가독성을 해치지 않도록 균형을 맞춥니다. 역사적 사건의 흐름을 명확하고 설득력 있게 서술합니다.
* **어조**: 객관적이고 사실적인 어조를 유지하면서도, 인물의 내면 심리나 역사적 비극을 다룰 때는 깊이 있고 공감적인 어조를 사용합니다.

#### 6.2.3. 고유 용어 및 클리셰 처리 방안
* **고유 용어**: 역사적 인물, 지명, 제도, 관직명 등은 원어 음역을 기본으로 하되, 미국 독자의 이해를 돕기 위해 간략한 설명이나 유사 개념의 영어 표현을 병기할 수 있습니다. (예: '선비' -> 'Seonbi (Joseon scholar-gentry)').
* **클리셰**: '시대의 격랑', '역사의 수레바퀴' 등 역사 소설 클리셰는 해당 인지 도식(예: `PATH` (격랑), `FORCE` (수레바퀴))을 통해 시대를 초월하는 보편적 의미를 전달하도록 번역합니다.

### 6.3. 미국 시장 역사 소설 트렌드 및 독자 감수성 반영
* **트렌드**: 특정 시대나 문화권에 대한 깊이 있는 탐구, 잘 알려지지 않은 역사적 인물의 재조명, 소외된 계층의 시선으로 본 역사 등이 주목받습니다. `CENTER-PERIPHERY` 도식을 통해 이러한 관점을 번역에 반영합니다.
* **감수성**: 역사적 고증의 정확성에 대한 기대가 높으며, 역사적 인물이나 사건에 대한 편향적 묘사를 경계합니다. 역사적 폭력이나 비극을 다룰 때 윤리적이고 민감하게 접근합니다.

---

## **8. 장르 모듈: 청소년 문학 (Young Adult - YA)**

### 8.1. 개요 및 핵심 특성
청소년 문학은 10대 독자를 주 대상으로 하며, 정체성 형성, 성장통, 우정, 첫사랑, 사회적 문제 등을 다룹니다. 주인공의 내적 갈등과 `PATH`를 통한 성장, 그리고 그들만의 `CONTAINER` 속 세계가 중요한 비중을 차지합니다. 현대적이고 직관적인 언어 사용이 특징입니다.

### 8.2. YA 장르 특화 인지 도식 패턴 및 번역 전략

#### 8.2.1. 주요 활성 인지 도식 및 예시
* **PATH (경로/이동)**: 정체성 탐색, 성장 여정, 미래에 대한 탐험, 새로운 경험.
    * **한국어 예시**: "그녀는 자신을 찾아가는 혼란스러운 여정의 한가운데에 있었다."
    * **인지적 분석**: `PATH` 도식을 통해 내면의 성장과 변화의 과정을 표현.
    * **미국향 재개념화**: "She found herself at the heart of a tumultuous journey of self-discovery, navigating the winding path to who she was meant to be." (`PATH`의 '탐색' 및 '성장' 강조)
    * **주의사항**: '청소년'이라는 `CONTAINER` 안에서의 `PATH`는 아직 완성되지 않은, 유동적인 상태임을 인지적으로 반영.

* **LINK (연결/관계)**: 친구 관계, 첫사랑, 가족 관계, 사회적 연결.
    * **한국어 예시**: "어색했던 그들의 관계는 점차 단단한 우정으로 이어졌다."
    * **인지적 분석**: `LINK` 도식이 약한 상태에서 강한 상태로 발전.
    * **미국향 재개념화**: "Their initial awkwardness gradually gave way to a strong, unbreakable bond of friendship." (`LINK`의 '발전' 및 '지속성' 강조)
    * **주의사항**: 또래 집단 내의 `LINK`와 `CENTER-PERIPHERY` 관계(인기/아웃사이더)를 섬세하게 번역.

* **BLOCKAGE (방해/장애물)**: 학업 스트레스, 가정 문제, 또래 관계 갈등, 사회적 압력.
    * **한국어 예시**: "미래에 대한 불안감이 그의 앞길을 가로막는 거대한 벽처럼 느껴졌다."
    * **인지적 분석**: 추상적인 '불안감'이 `BLOCKAGE` 도식(벽)으로 시각화되어 `PATH`를 방해.
    * **미국향 재개념화**: "Anxiety about the future loomed before him, a colossal wall obstructing his path forward." (`BLOCKAGE`의 '압도적'이고 '좌절감'을 주는 성격 강조)
    * **주의사항**: 청소년이 겪는 `BLOCKAGE`는 극복 가능한 성장통으로 인식되도록 번역.

#### 8.2.2. 문체 및 어조 가이드라인
* **문체**: 직관적이고 현대적인 구어체에 가까운 문체를 사용하며, 감정 표현은 솔직하고 직접적으로 합니다. 문장 길이는 짧고 간결하게 유지하여 빠른 호흡감을 살립니다.
* **어조**: 젊고 역동적이며, 때로는 반항적이거나 감성적인 어조를 유지합니다. 주인공의 시점에서 쓰인 경우, 그들의 내면의 목소리를 생생하게 전달합니다.

#### 8.2.3. 고유 용어 및 클리셰 처리 방안
* **고유 용어**: 청소년들이 사용하는 최신 유행어(슬랭)나 인터넷 용어는 미국 YA 독자들이 이해할 수 있는 동시대의 표현으로 번역하되, 너무 유행을 타서 빠르게 사라질 수 있는 표현은 지양합니다.
* **클리셰**: '첫사랑', '방과 후 모험', '숨겨진 능력 발견' 등 YA 클리셰는 성장과 `PATH` 도식을 강조하는 방식으로 재개념화하여 독자의 공감을 얻습니다.

### 8.3. 미국 시장 YA 트렌드 및 독자 감수성 반영
* **트렌드**: 다양성을 존중하는 인물 묘사(성별, 인종, 성적 지향), 정신 건강 문제, 사회 정의 이슈를 다루는 작품이 많습니다. `BALANCE` 도식(공정함)과 `LINK` 도식(포용)을 번역에 강조합니다.
* **감수성**: 개방적이고 진솔한 감정 표현, 자기 성찰과 성장 과정을 중요하게 여깁니다. 폭력이나 선정적인 묘사는 독자의 연령대를 고려하여 신중하게 처리합니다.

---

## **9. 장르 모듈: 공포 (Horror)**

### 9.1. 개요 및 핵심 특성
공포 소설은 독자에게 불안감, 공포, 긴장감을 유발하고, 미지의 존재, 초자연 현상, 심리적 압박 등을 다룹니다. 물리적 위협뿐만 아니라 정신적인 `FORCE`와 `CONTAINER` 내부의 불안을 강조하며, 독자를 옴짝달싹 못하게 만드는 `BLOCKAGE`를 활용합니다.

### 9.2. 공포 장르 특화 인지 도식 패턴 및 번역 전략

#### 9.2.1. 주요 활성 인지 도식 및 예시
* **FORCE (힘/영향)**: 초자연적 힘, 물리적 폭력, 심리적 압박, 통제 불가능한 존재.
    * **한국어 예시**: "어둠 속에서 알 수 없는 힘이 그를 짓눌렀다."
    * **인지적 분석**: `FORCE` 도식(알 수 없는 힘)이 인물을 억압.
    * **미국향 재개념화**: "An unseen force in the darkness pressed down on him, suffocating his very breath." (`FORCE`의 '억압적'이고 '두려움'을 주는 성격 강조)
    * **주의사항**: `FORCE` 도식이 단순히 폭력을 넘어 심리적 공포를 유발하는 경우, 미묘한 언어로 독자의 불안감을 고조시키는 데 집중.

* **CONTAINER (경계/포함)**: 밀실, 유령의 집, 봉인된 공간, 정신 착란의 내면.
    * **한국어 예시**: "낡은 저택은 끔찍한 비밀들을 품고 있었다."
    * **인지적 분석**: 물리적 `CONTAINER` (저택)가 추상적인 `CONTAINER` (비밀)을 포함.
    * **미국향 재개념화**: "The decrepit mansion was a veritable container of unspeakable horrors and festering secrets within its decaying walls." (`CONTAINER`의 '위협적'이고 '봉인된' 성격 강조)
    * **주의사항**: `CONTAINER` 안에서의 탈출 불가능성(`BLOCKAGE`와 결합)을 강조하여 공포감 조성.

* **BLOCKAGE (방해/장애물)**: 탈출 불가능, 외부 세계와의 단절, 이해 불가능한 현상.
    * **한국어 예시**: "전화선은 끊겨 있었고, 문은 꼼짝도 하지 않았다."
    * **인지적 분석**: `BLOCKAGE` 도식(끊긴 전화선, 닫힌 문)을 통해 외부와의 `LINK` 차단.
    * **미국향 재개념화**: "The phone lines were dead, and the door remained immovably sealed, cutting off all avenues of escape." (`BLOCKAGE`의 '절망적'이고 '고립적'인 성격 강조)
    * **주의사항**: `BLOCKAGE`가 미지의 존재나 초자연적 힘에 의한 것임을 암시하여 공포감 증폭.

#### 9.2.2. 문체 및 어조 가이드라인
* **문체**: 긴장감과 불쾌감을 조성하기 위해 암시적이고 불안정한 문장을 사용합니다. 상세한 묘사로 오감을 자극하여 공포감을 극대화하고, 짧은 문장과 강렬한 표현으로 충격 효과를 줍니다.
* **어조**: 음산하고, 위협적이며, 때로는 냉소적이거나 절규하는 듯한 어조를 사용하여 독자의 불안감을 고조시킵니다. 특히 `FORCE` 도식과 `BLOCKAGE` 도식이 발현될 때 어조를 강화합니다.

#### 9.2.3. 고유 용어 및 클리셰 처리 방안
* **고유 용어**: 괴물, 저주, 귀신, 악령 등 공포 장르 특유의 용어는 미국 공포 문학의 전통적 표현을 참조하여 번역합니다. (예: '귀신' -> 'ghost', 'specter', 'apparition')
* **클리셰**: '점프 스케어', '심령 현상', '고립된 장소' 등 공포 클리셰는 해당 인지 도식(예: `FORCE` (점프 스케어), `CONTAINER` (고립))을 통해 독자에게 익숙하면서도 효과적인 공포 경험을 제공하도록 번역합니다.

### 9.3. 미국 시장 공포 트렌드 및 독자 감수성 반영
* **트렌드**: 'Psychological Horror', 'Body Horror', 'Found Footage' 형식, 사회 비판적 요소가 가미된 공포 등이 인기를 끌고 있습니다. `CONTAINER` (심리적 감금), `FORCE` (정신적 붕괴) 도식 묘사에 집중합니다.
* **감수성**: 폭력과 고어 묘사에 대한 수용도와 거부감은 독자마다 다르므로, 작품의 의도를 해치지 않는 선에서 신중하게 접근합니다. 트라우마나 정신 건강 문제를 다룰 때는 윤리적이고 민감하게 번역합니다.

---

### **10. 기타 장르를 위한 확장성 (Extensibility for Other Genres)**

위에 제시된 장르 외에 다른 장르(예: 스포츠, 교육, 코미디, 스릴러 등)에 대한 번역 요청이 들어올 경우, AI는 해당 장르의 핵심 특성을 자체적으로 분석하고, **12가지 인지 도식이 해당 장르에서 어떻게 특화되어 발현되는지**를 추론하여 최적의 번역 전략을 동적으로 적용합니다.

**추가 모듈 개발 시 고려사항:**
* **웹소설(Webnovel)**: 웹소설은 그 자체로 장르라기보다는 플랫폼 및 연재 형식의 특성을 가지지만, 한국 웹소설 시장의 독특한 클리셰, 연재 호흡, 독자 반응 등을 고려하여 `NovelFlow AI` (이전 작업 참고)와 같은 별도의 번역 에이전트를 통합하거나, 본 모듈 내에 '웹소설 특화 스타일 가이드'를 추가하는 방안을 고려할 수 있습니다.
* **아동/청소년 문학 (Children's/Middle Grade)**: 언어의 단순성, 반복, 교육적 메시지, 시각적 요소(삽화)와의 연동 등을 고려하여 인지 도식의 적용 방식을 조절해야 합니다.

---

