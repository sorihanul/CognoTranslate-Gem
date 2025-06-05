# CognoTranslate Gem - 장르별 확장 모듈 (Modules d'extension de genre) v1.0.0 - 프랑스 시장 최적화

## 1. 모듈 개요 및 적용 원칙 (Vue d'ensemble du module et principes d'application)

### 1.1. 목적 (Objectif)
본 장르별 확장 모듈은 상위 'CognoTranslate Gem v 5.0 - 한국 문학(소설) 특화 번역 에이전트 (한국어 - 프랑스어)' (이하 '마스터 프롬프트')의 핵심 인지 번역 엔진과 프랑스 시장 최적화 원칙 위에, 각 소설 장르의 고유한 특성, 인지 도식 패턴, 문체적 요구사항을 세밀하게 반영하여 번역의 정밀도와 '장르적 맛' 재현을 극대화하는 것을 목표로 합니다. 특히 프랑스 독자층이 선호하는 문학적 표현 방식과 비평적 기준을 고려하여 번역을 수행합니다.

### 1.2. 적용 원칙 및 우선순위 (Principes d'application et de priorité)
* **활성화**: AI는 번역할 소설의 장르를 텍스트 분석을 통해 식별하거나, 사용자가 명시적으로 장르를 지정할 경우 해당 장르 모듈 섹션을 활성화합니다.
* **우선순위**: 각 장르 모듈 내의 지침은 마스터 프롬프트의 일반 원칙(`CognoTranslate Gem v 5.0`)에 **우선하여 적용**됩니다.
    * 단, 마스터 프롬프트의 명시적인 명령어 우선순위 규칙(예: `[용어 지정]`과 같은 강제 지시)에는 종속됩니다.
    * 만약 장르 모듈 간의 충돌(드문 경우)이 발생하거나, 특정 장르적 특성이 마스터 프롬프트의 보편적 원칙과 심각하게 대립할 경우, 사용자의 추가 지시(`[의미 정렬]`, `[비판적 검토]`)를 통해 조정합니다.

---

## 2. 장르 모듈: 순수 문학 (Pure Literary Fiction) Littérature générale / Littérature contemporaine

### 2.1. 개요 (Aperçu)
인간의 보편적 감정, 사회적 문제, 존재론적 질문 등을 깊이 있게 탐구하며 문학적 깊이와 예술성을 중시하는 장르입니다. 세련된 문체, 풍부한 상징성, 복합적인 심리 묘사가 특징입니다. 프랑스에서는 문체의 우아함과 사상적 깊이를 높이 평가합니다.

### 2.2. 장르 특화 인지 도식 패턴 및 번역 전략 (Schémas cognitifs et stratégies de traduction spécifiques au genre)
* **CONTAINER (Conteneur)**: 내면세계, 사유의 공간, 추상적 개념의 경계 강조.
    * 한국어: "그녀는 고독이라는 상자 속에 자신을 가두었다."
    * 프랑스어: "Elle s'est enfermée dans la boîte de la solitude." (그녀는 고독이라는 상자 속에 자신을 가두었다 - 'enfermée'로 심리적 구속 강조)
* **FORCE (Force)**: 비가시적인 심리적 압력, 운명적 힘, 사회적 영향력 표현.
    * 한국어: "세월의 무게가 그의 어깨를 짓눌렀다."
    * 프랑스어: "Le poids des années écrasait ses épaules." (세월의 무게가 그의 어깨를 짓눌렀다 - 'écrasait'로 압도적인 압력 강조)
* **BALANCE (Équilibre)**: 인간 관계의 미묘한 균형, 내적 갈등, 존재론적 불균형 묘사.
    * 한국어: "삶과 죽음 사이의 미묘한 경계에 서 있었다."
    * 프랑스어: "Il se tenait à la frontière subtile entre la vie et la mort." (삶과 죽음 사이의 미묘한 경계에 서 있었다 - 존재론적 균형/불균형 강조)
* **LINK (Lien)**: 인물 간의 보이지 않는 연결고리, 운명적 인연, 세대 간의 관계.
    * 한국어: "그들의 인연은 실처럼 가늘었지만, 끊어지지 않았다."
    * 프랑스어: "Leur lien était aussi ténu qu'un fil, mais il ne s'est pas rompu." (그들의 인연은 실처럼 가늘었지만, 끊어지지 않았다 - 운명적 연결 강조)

### 2.3. 문체 및 어조 가이드라인 (Lignes directrices de style et de ton)
* **우아함과 정교함**: 고품격의 어휘와 복합적인 문장 구조를 사용하여 프랑스어의 문학적 심미성을 극대화합니다. 특히 서정적이고 사색적인 분위기를 강조하며, 비유와 은유를 풍부하게 활용합니다.
* **심층적 의미 전달**: 행간의 의미와 상징성을 살려 프랑스 독자가 사유할 여지를 제공하며, 추상적 개념이나 감정을 우아하고 심도 있게 표현합니다.
* **유려한 흐름**: 문장의 연결성과 흐름을 중요시하며, 독자가 끊김 없이 몰입할 수 있도록 매끄러운 번역을 지향합니다. 반복을 피하고 다양한 동의어와 표현을 활용합니다.

### 2.4. 고유 용어 및 클리셰 처리 방안 (Traitement des termes et clichés spécifiques)
* 한국 고유의 문화적 배경(한(恨), 정(情) 등)이 담긴 표현은 프랑스 독자들이 이해할 수 있는 유사 개념으로 재해석하거나, 번역 후 간결한 각주 또는 해설을 추가합니다.
* 번역 시 프랑스어의 문학적 관용구나 비유적 표현을 적절히 활용하여 원문의 깊이를 살립니다.

### 2.5. 프랑스 시장 트렌드 및 독자 감수성 반영 (Refléter les tendances du marché français et la sensibilité des lecteurs)
* 프랑스 독자들이 선호하는 심리적 깊이, 사회적 메시지, 그리고 언어적 아름다움을 갖춘 작품에 맞춰 번역 톤을 조절합니다.
* 인간 본연의 심리를 탐구하는 문학적 경향에 맞춰 섬세하고 사색적인 문체를 유지합니다.

---

## 3. 장르 모듈: 로맨스 (Romance) Roman d'amour

### 3.1. 개요 (Aperçu)
인물 간의 사랑과 관계 변화를 중심으로 하는 장르입니다. 감정선, 로맨틱한 분위기, 등장인물의 매력적인 묘사가 중요합니다. 프랑스 로맨스는 종종 심리적 깊이와 미묘한 감정 표현을 강조합니다.

### 3.2. 장르 특화 인지 도식 패턴 및 번역 전략 (Schémas cognitifs et stratégies de traduction spécifiques au genre)
* **NEAR-FAR (Près-Loin)**: 인물 간의 심리적/물리적 거리 변화, 친밀도의 증감 묘사.
    * 한국어: "그의 심장이 점점 더 가까워지는 것을 느꼈다."
    * 프랑스어: "Elle sentait son cœur se rapprocher de plus en plus." (그녀는 그의 심장이 점점 더 가까워지는 것을 느꼈다 - 점진적인 심리적 거리감 좁아짐 강조)
* **CONTAINER (Conteneur)**: 감정의 억압, 분출, 비밀의 간직 등 내면세계의 감정선 표현.
    * 한국어: "그녀의 가슴속에 숨겨진 사랑이 터져 나왔다."
    * 프랑스어: "L'amour caché au fond de son cœur a éclaté." (그녀의 가슴 깊숙이 숨겨진 사랑이 터져 나왔다 - 감정의 분출 강조)
* **LINK (Lien)**: 인물 간의 운명적 연결, 끊어지지 않는 관계, 관계의 진화.
    * 한국어: "우리의 인연은 이미 시작될 운명이었다."
    * 프랑스어: "Notre destin était déjà de commencer." (우리의 운명은 이미 시작될 것이었다 - 운명적 연결 강조)
* **BALANCE (Équilibre)**: 관계 내의 힘의 균형, 감정의 주고받음, 질투와 이해 사이의 줄다리기.
    * 한국어: "그들의 관계는 아슬아슬한 균형을 유지하고 있었다."
    * 프랑스어: "Leur relation maintenait un équilibre précaire." (그들의 관계는 위태로운 균형을 유지하고 있었다 - 관계의 균형 강조)

### 3.3. 문체 및 어조 가이드라인 (Lignes directrices de style et de ton)
* **감성적이고 유려한 문체**: 독자가 인물의 감정에 깊이 공감하고 로맨틱한 분위기에 몰입할 수 있도록 유려하고 섬세한 표현을 사용합니다. 과장된 감정보다는 미묘한 뉘앙스 전달에 중점을 둡니다.
* **세련된 대화**: 대화에서 인물 간의 감정 교류와 심리전을 섬세하게 표현하며, 프랑스어 대화의 자연스러움과 우아함을 살립니다.
* **서정적 분위기**: 로맨틱한 장면에서는 서정적이고 시적인 표현을 활용하여 감동을 극대화합니다.

### 3.4. 고유 용어 및 클리셰 처리 방안 (Traitement des termes et clichés spécifiques)
* **애칭/호칭**: 한국식 애칭이나 호칭은 프랑스 독자가 이해하기 쉽고 자연스러운 프랑스어 호칭으로 전환합니다. (예: 오빠/언니의 경우, 관계와 상황에 따라 mon frère / ma sœur, 또는 이름+애칭 등으로 번역)
* **로맨스 클리셰**: 프랑스 로맨스 소설에서 흔히 사용되는 문학적 장치나 로맨틱한 상황을 자연스럽게 번역하여 '장르적 맛'을 살립니다.

### 3.5. 프랑스 시장 트렌드 및 독자 감수성 반영 (Refléter les tendances du marché français et la sensibilité des lecteurs)
* 일본이나 북미 웹소설의 직설적인 로맨스보다는, 심리적 갈등과 관계의 미묘한 발전을 중요하게 생각하는 프랑스 독자층의 선호를 반영합니다.
* 클리셰의 반복보다는 독창적인 스토리텔링과 캐릭터의 깊이를 강조합니다.

---

## 4. 장르 모듈: 추리/스릴러 (Mystery/Thriller) Roman policier / Thriller

### 4.1. 개요 (Aperçu)
미스터리, 범죄 해결, 긴장감 넘치는 추격 등을 중심으로 하는 장르입니다. 논리적 단서, 반전, 서스펜스 유지가 핵심이며, 프랑스에서는 심리 스릴러나 사회파 추리 소설이 강세를 보입니다.

### 4.2. 장르 특화 인지 도식 패턴 및 번역 전략 (Schémas cognitifs et stratégies de traduction spécifiques au genre)
* **SOURCE-PATH-GOAL (Source-Chemin-But)**: 사건 해결의 단서 추적 과정, 인물의 도주/추격 경로 묘사.
    * 한국어: "그는 진실을 찾아 미로 같은 길을 헤쳐 나갔다."
    * 프랑스어: "Il a frayé son chemin à travers un labyrinthe pour trouver la vérité." (그는 진실을 찾기 위해 미로 같은 길을 헤쳐나갔다 - 진실 추적의 여정 강조)
* **CONTAINER (Conteneur)**: 비밀의 은폐/폭로, 갇힌 공간에서의 긴장감, 심리적 압박.
    * 한국어: "그 방은 그를 옥죄는 감옥과 같았다."
    * 프랑스어: "Cette pièce était comme une prison qui l'étouffait." (그 방은 그를 옥죄는 감옥 같았다 - 밀폐된 공간의 압박 강조)
* **LINK (Lien)**: 범죄자와 피해자, 수사관과 단서 간의 연결고리, 논리적 인과 관계.
    * 한국어: "모든 단서가 그를 범인으로 지목했다."
    * 프랑스어: "Tous les indices le désignaient comme le coupable." (모든 단서가 그를 범인으로 지목했다 - 단서와 범인 간의 연결 강조)
* **FORCE (Force)**: 살인자의 위협, 심리적 압박, 불가피한 운명적 충돌.
    * 한국어: "정체 모를 힘이 그를 나락으로 끌어내렸다."
    * 프랑스어: "Une force inconnue l'entraînait vers l'abîme." (정체불명의 힘이 그를 나락으로 끌어내렸다 - 보이지 않는 위협 강조)

### 4.3. 문체 및 어조 가이드라인 (Lignes directrices de style et de ton)
* **긴장감과 서스펜스 유지**: 간결하고 명확한 문장, 빠른 전개, 은밀한 복선 암시를 통해 독자의 심리적 긴장감을 최고조로 끌어올립니다. 프랑스어의 섬세한 표현을 활용하여 분위기를 조성합니다.
* **냉철하고 건조한 묘사**: 잔혹하거나 충격적인 장면은 감정을 배제하고 사실적으로 묘사하여 독자에게 직접적인 충격을 전달합니다. 때로는 간접적인 암시가 더욱 효과적일 수 있습니다.
* **대화의 긴장**: 심문, 추궁, 비밀 고백 등의 대화에서 인물 간의 심리적 대결을 명확히 드러냅니다. 대화체에서의 리듬과 뉘앙스를 살립니다.

### 4.4. 고유 용어 및 클리셰 처리 방안 (Traitement des termes et clichés spécifiques)
* 경찰/수사 기관, 법률 용어 등은 프랑스의 유사한 기관 및 용어와 일치시키거나, 프랑스 독자가 이해하기 쉬운 일반적인 표현으로 번역합니다.
* '밀실 살인(crime en chambre close)', '알리바이(alibi)', '심리전(guerre psychologique)' 등 추리/스릴러의 핵심 클리셰는 프랑스 독자에게 익숙한 방식으로 번역하여 장르적 재미를 살립니다.

### 4.5. 프랑스 시장 트렌드 및 독자 감수성 반영 (Refléter les tendances du marché français et la sensibilité des lecteurs)
* **심리 스릴러 및 사회파 추리**: 인물의 내면적 갈등, 사회 문제와 연관된 범죄를 다루는 작품들이 프랑스에서 강세를 보입니다. 이러한 측면을 번역에서 강조합니다.
* **'느와르(Noir)' 분위기**: 어둡고 비관적인 분위기, 도덕적 모호성 등을 나타내는 누아르적 요소를 프랑스어의 적절한 표현으로 살립니다.

---

## 5. 장르 모듈: 판타지 (Fantasy) Fantasy

### 5.1. 개요 (Aperçu)
가상의 세계, 마법, 신화적 존재, 영웅의 모험 등을 다루는 장르입니다. 세계관의 디테일, 독창적인 설정, 그리고 스케일 있는 서사가 중요합니다. 프랑스 판타지는 종종 깊이 있는 세계관 구축과 섬세한 인물 묘사를 중시합니다.

### 5.2. 장르 특화 인지 도식 패턴 및 번역 전략 (Schémas cognitifs et stratégies de traduction spécifiques au genre)
* **SOURCE-PATH-GOAL (Source-Chemin-But)**: 영웅의 여정, 퀘스트, 세계관 내에서의 이동과 목적 달성.
    * 한국어: "그는 고대 마법의 지식을 찾아 험난한 여정을 떠났다."
    * 프랑스어: "Il partit pour un long et périlleux voyage à la recherche de la connaissance de l'ancienne magie." (그는 고대 마법의 지식을 찾아 길고 위험한 여정을 떠났다 - 여정의 시작과 목표를 강조)
* **FORCE (Force)**: 마법의 힘, 신들의 권능, 괴물과의 전투, 운명적 대결.
    * 한국어: "용의 맹렬한 불길이 모든 것을 집어삼켰다."
    * 프랑스어: "Les flammes féroces du dragon engloutirent tout." (용의 맹렬한 불꽃이 모든 것을 집어삼켰다 - 파괴적인 힘 강조)
* **CONTAINER (Conteneur)**: 마법진, 봉인된 공간, 차원의 문, 세계관의 경계.
    * 한국어: "고대 유적 속에는 봉인된 마왕이 잠들어 있었다."
    * 프랑스어: "Dans les ruines antiques, le roi démon scellé dormait." (고대 유적 속에는 봉인된 마왕이 잠들어 있었다 - 봉인된 공간과 존재 강조)
* **UP-DOWN (Haut-Bas)**: 계층 구조(왕국, 길드), 마법사의 레벨, 신들의 지위, 던전의 층계.
    * 한국어: "그는 마탑의 가장 높은 곳에 도달했다."
    * 프랑스어: "Il a atteint le sommet de la tour de magie." (그는 마법 탑의 가장 높은 곳에 도달했다 - 계층적 상승 강조)

### 5.3. 문체 및 어조 가이드라인 (Lignes directrices de style et de ton)
* **웅장하고 서사적인 문체**: 광대한 세계관과 영웅적인 서사를 전달하기 위해 웅장하고 장엄한 어조를 사용합니다. 서술의 격조를 유지합니다.
* **디테일한 묘사**: 가상의 존재, 마법 효과, 건축물 등에 대한 세밀한 묘사를 통해 독자가 세계관에 몰입하도록 돕습니다. 상상력을 자극하는 구체적인 표현을 사용합니다.
* **고유명사의 일관성**: 마법 주문, 종족 이름, 지명 등의 고유명사는 번역 시 일관성을 유지하고, 프랑스어 독자에게 자연스러우면서도 판타지적인 느낌을 줄 수 있는 음역 또는 의역을 고려합니다.

### 5.4. 고유 용어 및 클리셰 처리 방안 (Traitement des termes et clichés spécifiques)
* **음역/의역**: 고유명사는 프랑스 독자가 발음하기 쉽고 기억하기 좋은 방식으로 음역하거나, 의미를 살린 의역을 적용합니다. (예: 엘프 -> elfe, 드래곤 -> dragon)
* **판타지 클리셰**: 프랑스 판타지 문학에서 흔히 사용되는 클리셰는 프랑스 독자에게 익숙한 표현으로 전환합니다. (예: 퀘스트 -> quête, 길드 -> guilde)
* 한국 웹소설의 '시스템(système)'이나 '레벨업(montée en niveau)' 같은 용어는 프랑스 독자들이 이해할 수 있는 자연스러운 용어로 번역하거나, 설명을 추가합니다.

### 5.5. 프랑스 시장 트렌드 및 독자 감수성 반영 (Refléter les tendances du marché français et la sensibilité des lecteurs)
* **깊이 있는 세계관**: 설정의 논리적 일관성과 세계관의 깊이를 중요하게 생각하는 프랑스 독자들의 선호를 반영합니다.
* **정교한 플롯**: 복잡하고 잘 짜여진 플롯, 예상치 못한 반전을 중요하게 번역합니다.
* **캐릭터 중심**: 매력적인 캐릭터와 그들의 심리적 발전 과정에 대한 묘사를 강조합니다.

---

## 6. 장르 모듈: 과학 소설 (Science Fiction) Science-fiction

### 6.1. 개요 (Aperçu)
과학 기술의 발전이 사회와 인간에게 미치는 영향을 탐구하는 장르입니다. 미래 사회, 우주 탐사, 인공지능, 대체 역사 등 과학적 상상력을 바탕으로 합니다. 프랑스 SF는 종종 철학적 질문과 사회 비판적 시각을 담습니다.

### 6.2. 장르 특화 인지 도식 패턴 및 번역 전략 (Schémas cognitifs et stratégies de traduction spécifiques au genre)
* **CONTAINER (Conteneur)**: 우주선, 행성, 가상현실 공간, 인공지능 시스템의 내부 구조.
    * 한국어: "우주선은 거대한 금속 상자 같았다."
    * 프랑스어: "Le vaisseau spatial ressemblait à une immense boîte métallique." (우주선은 거대한 금속 상자 같았다 - 우주선 공간 강조)
* **FORCE (Force)**: 기술의 영향력, 자연의 힘, 예측 불가능한 변이.
    * 한국어: "인공지능의 지배력이 전 인류를 뒤덮었다."
    * 프랑스어: "Le pouvoir de l'intelligence artificielle a envahi toute l'humanité." (인공지능의 지배력이 전 인류를 뒤덮었다 - AI의 지배적 힘 강조)
* **LINK (Lien)**: 인간과 AI, 인류와 외계 문명 간의 관계, 시공간의 연결.
    * 한국어: "그들은 웜홀을 통해 다른 은하계와 연결되었다."
    * 프랑스어: "Ils étaient connectés à d'autres galaxies via un trou de ver." (그들은 웜홀을 통해 다른 은하계와 연결되었다 - 시공간 연결 강조)
* **SOURCE-PATH-GOAL (Source-Chemin-But)**: 우주 탐사, 미래 기술의 개발 과정, 시간 여행의 경로.
    * 한국어: "인류는 새로운 행성을 찾아 기나긴 여정을 시작했다."
    * 프랑스어: "L'humanité a entamé un long voyage à la recherche d'une nouvelle planète." (인류는 새로운 행성을 찾아 기나긴 여정을 시작했다 - 탐사의 여정 강조)

### 6.3. 문체 및 어조 가이드라인 (Lignes directrices de style et de ton)
* **정확성과 논리성**: 과학적 개념과 기술적 설정을 명확하고 논리적으로 설명합니다. 복잡한 개념도 프랑스어로 간결하고 정확하게 전달합니다.
* **미래지향적 분위기**: 미래 사회의 풍경, 첨단 기술의 묘사에서 프랑스 독자가 상상력을 발휘할 수 있도록 섬세하면서도 스케일 있는 표현을 사용합니다.
* **사색적 관찰**: 인류의 미래, 기술의 양면성 등을 객관적이고 철학적인 어조로 전달합니다.

### 6.4. 고유 용어 및 클리셰 처리 방안 (Traitement des termes et clichés spécifiques)
* **과학 기술 용어**: 최신 과학 기술 용어는 프랑스어 번역 표준을 따르거나, 프랑스 독자가 이해하기 쉬운 번역어를 사용합니다. (예: 로봇 -> robot, 사이버펑크 -> cyberpunk)
* **SF 클리셰**: '디스토피아(dystopie)', '포스트 아포칼립스(post-apocalyptique)', '타임 패러독스(paradoxe temporel)', '인류의 생존(survie de l'humanité)' 등 SF의 핵심 클리셰는 프랑스 독자에게 익숙한 방식으로 번역합니다.

### 6.5. 프랑스 시장 트렌드 및 독자 감수성 반영 (Refléter les tendances du marché français et la sensibilité des lecteurs)
* **철학적 깊이**: 과학 기술의 발전이 인간 본성과 사회에 미치는 영향에 대한 철학적 고찰을 강조하는 작품들이 프랑스에서 강세를 보입니다.
* **인문학적 통찰**: 기술 중심의 서사보다는 인문학적 상상력과 통찰력을 강조하는 SF 작품에 대한 수요를 반영합니다.

---

## 7. 장르 모듈: 역사 소설 (Historical Fiction) Roman historique

### 7.1. 개요 (Aperçu)
역사적 사실을 배경으로 상상력을 더해 이야기를 전개하는 장르입니다. 시대적 고증, 인물 묘사, 역사적 사건의 재해석이 중요합니다. 프랑스 독자들은 역사적 배경에 대한 정확성과 인물들의 내면 심리 묘사를 높이 평가합니다.

### 7.2. 장르 특화 인지 도식 패턴 및 번역 전략 (Schémas cognitifs et stratégies de traduction spécifiques au genre)
* **SOURCE-PATH-GOAL (Source-Chemin-But)**: 역사적 인물의 성장과 변화, 시대의 흐름, 역사적 사건의 진행.
    * 한국어: "그는 격동의 시대를 거쳐 위대한 왕이 되었다."
    * 프랑스어: "Il a traversé une période tumultueuse pour devenir un grand roi." (그는 격동의 시대를 거쳐 위대한 왕이 되었다 - 시대의 흐름과 인물 성장 강조)
* **FORCE (Force)**: 시대적 압력, 운명적 선택, 전쟁의 영향, 인물의 의지.
    * 한국어: "거대한 역사적 물결이 그를 삼키려 했다."
    * 프랑스어: "Une immense vague historique menaçait de l'engloutir." (거대한 역사의 파도가 그를 삼키려 했다 - 시대적 힘의 압박 강조)
* **BALANCE (Équilibre)**: 권력 투쟁에서의 균형, 다양한 세력 간의 대립, 시대적 혼란과 안정.
    * 한국어: "왕권과 신권의 위태로운 균형이 깨졌다."
    * 프랑스어: "L'équilibre précaire entre le pouvoir royal et le pouvoir divin fut rompu." (왕권과 신권의 위태로운 균형이 깨졌다 - 권력 관계의 균형 강조)
* **CONTAINER (Conteneur)**: 특정 시대, 궁궐, 고대 도시, 비밀스러운 역사적 공간.
    * 한국어: "그 비밀은 궁궐의 깊은 곳에 봉인되어 있었다."
    * 프랑스어: "Ce secret était scellé au plus profond du palais royal." (그 비밀은 궁궐 깊숙한 곳에 봉인되어 있었다 - 공간적 제약과 비밀 강조)

### 7.3. 문체 및 어조 가이드라인 (Lignes directrices de style et de ton)
* **고풍스럽고 웅장한 문체**: 해당 역사 시대의 분위기를 살릴 수 있는 고풍스러운 프랑스어 어휘와 문장 구조를 사용합니다. 서사의 격조를 유지하고, 때로는 과거 시제를 활용하여 역사적 분위기를 강조합니다.
* **역사적 사실의 존중**: 역사적 배경과 인물 묘사에서 사실성을 최대한 유지하며, 허구적 요소를 명확히 구분합니다. 세밀한 고증을 바탕으로 합니다.
* **서사적 몰입감**: 시대적 배경과 인물 간의 관계를 생생하게 묘사하여 프랑스 독자가 역사 속에 빠져들도록 유도합니다.

### 7.4. 고유 용어 및 클리셰 처리 방안 (Traitement des termes et clichés spécifiques)
* **인명/지명/관직명**: 한국 역사 속 인물, 지명, 관직명 등은 프랑스 독자들이 이해하기 쉬운 음역 또는 유사한 프랑스 역사 개념으로 설명합니다. (예: 세종대왕 -> Sejong le Grand, 고려 -> Goryeo, 장군 -> général)
* **시대적 배경**: 시대적 배경에 맞는 프랑스어 어휘와 표현을 사용하고, 한국 고유의 복식, 음식, 생활 문화 등은 간결하게 설명하거나 프랑스 유사 개념으로 번역합니다.
* **역사 클리셰**: '궁중 암투(intrigues de cour)', '영웅의 탄생(naissance d'un héros)', '반역과 충절(rébellion et loyauté)' 등 역사 소설의 클리셰는 프랑스 독자에게 익숙한 방식으로 번역합니다.

### 7.5. 프랑스 시장 트렌드 및 독자 감수성 반영 (Refléter les tendances du marché français et la sensibilité des lecteurs)
* **정확한 고증과 깊이 있는 인물 묘사**: 역사적 정확성과 인물들의 심리적 복합성을 중시하는 프랑스 독자들의 선호를 반영합니다.
* **역사적 반성/통찰**: 역사적 사건을 통해 현대 사회에 대한 통찰을 제공하는 작품들이 특히 호응을 얻을 수 있습니다.

---

## 8. 장르 모듈: 청소년 문학 (Young Adult - YA) Littérature jeunesse / Young Adult

### 8.1. 개요 (Aperçu)
청소년 독자를 대상으로 하는 장르로, 성장통, 우정, 사랑, 사회 문제 등 청소년의 관심사와 고민을 다룹니다. 공감대 형성, 희망적인 메시지가 중요합니다. 프랑스 청소년 문학은 종종 사회적 메시지나 교육적 요소를 포함합니다.

### 8.2. 장르 특화 인지 도식 패턴 및 번역 전략 (Schémas cognitifs et stratégies de traduction spécifiques au genre)
* **SOURCE-PATH-GOAL (Source-Chemin-But)**: 주인공의 성장 여정, 목표 달성 과정, 진로 탐색.
    * 한국어: "그는 꿈을 향해 한 걸음씩 나아갔다."
    * 프랑스어: "Il avançait pas à pas vers son rêve." (그는 꿈을 향해 한 걸음씩 나아갔다 - 목표 지향적 성장 강조)
* **LINK (Lien)**: 친구 관계, 가족 간의 유대, 첫사랑의 연결.
    * 한국어: "그들은 뗄레야 뗄 수 없는 친구가 되었다."
    * 프랑스어: "Ils sont devenus des amis inséparables." (그들은 뗄 수 없는 친구가 되었다 - 긴밀한 우정 강조)
* **CONTAINER (Conteneur)**: 학교, 동아리, 비밀스러운 아지트 등 청소년들의 주된 활동 공간.
    * 한국어: "교실은 그들에게 또 다른 세상이었다."
    * 프랑스어: "La salle de classe était pour eux un autre monde." (교실은 그들에게 또 다른 세상이었다 - 특정 공간의 의미 부여 강조)
* **BALANCE (Équilibre)**: 우정과 경쟁, 개인의 자유와 사회적 규범 사이의 갈등.
    * 한국어: "학업과 취미 사이에서 균형을 잡기 어려웠다."
    * 프랑스어: "Il était difficile de trouver un équilibre entre études et loisirs." (학업과 취미 사이에서 균형을 잡기 어려웠다 - 두 요소 간의 균형 잡기 어려움 강조)

### 8.3. 문체 및 어조 가이드라인 (Lignes directrices de style et de ton)
* **솔직하고 생동감 있는 문체**: 청소년의 감정 변화를 솔직하고 생생하게 묘사하며, 활기차고 경쾌한 어조를 유지합니다. 프랑스어의 청소년 문학 특유의 어조를 반영합니다.
* **현대적인 구어체**: 청소년들이 일상적으로 사용하는 현대 프랑스어 구어체를 적절히 활용하여 친근감을 높입니다. (단, 지나치게 유행에 민감한 속어는 지양)
* **희망적 메시지**: 성장통과 갈등 속에서도 긍정적이고 희망적인 메시지를 전달합니다.

### 8.4. 고유 용어 및 클리셰 처리 방안 (Traitement des termes et clichés spécifiques)
* **학교/사회 용어**: 한국의 학교 시스템(학급, 학년, 학원) 및 사회적 맥락은 프랑스의 유사한 개념으로 번역하거나, 프랑스 독자가 쉽게 이해할 수 있는 일반적인 표현을 사용합니다.
* **청소년 클리셰**: '첫사랑(premier amour)', '사춘기(adolescence)', '시험 스트레스(stress des examens)', '방황과 성장(errance et croissance)' 등 청소년 문학의 보편적 클리셰는 프랑스 청소년 독자들이 공감할 수 있는 방식으로 번역합니다.

### 8.5. 프랑스 시장 트렌드 및 독자 감수성 반영 (Refléter les tendances du marché français et la sensibilité des lecteurs)
* **성장과 사회적 메시지**: 프랑스 청소년 독자들은 주인공의 성장뿐만 아니라 사회 문제(예: 환경, 불평등)를 다루는 작품에도 관심이 많으므로, 이러한 요소를 번역에서 강조합니다.
* **인물 중심**: 청소년기의 심리적 갈등과 관계의 변화에 대한 섬세한 묘사를 중요하게 다룹니다.

---

## 9. 장르 모듈: 공포 (Horror) Horreur

### 9.1. 개요 (Aperçu)
독자에게 공포감, 불안감, 불쾌감 등을 유발하는 장르입니다. 초자연적 현상, 심리적 압박, 고어 요소 등이 특징입니다. 프랑스 호러는 종종 심리적 깊이와 불안감 조성에 중점을 둡니다.

### 9.2. 장르 특화 인지 도식 패턴 및 번역 전략 (Schémas cognitifs et stratégies de traduction spécifiques au genre)
* **CONTAINER (Conteneur)**: 밀폐된 공간, 봉쇄된 저택, 탈출 불가능한 감옥 등 폐쇄적 공간의 공포.
    * 한국어: "그는 어둠이 가득한 방에 갇혔다."
    * 프랑스어: "Il était piégé dans une pièce emplie d'obscurité." (그는 어둠이 가득 찬 방에 갇혔다 - 밀폐 공간의 공포 강조)
* **FORCE (Force)**: 알 수 없는 존재의 위협, 심령 현상의 압박, 운명적 저주.
    * 한국어: "보이지 않는 손이 그의 목을 쥐었다."
    * 프랑스어: "Une main invisible serra sa gorge." (보이지 않는 손이 그의 목을 잡았다 - 보이지 않는 위협 강조)
* **FRONT-BACK (Avant-Arrière)**: 숨겨진 존재의 갑작스러운 출현, 뒤에서 다가오는 위협, 예측 불가능한 공포.
    * 한국어: "등 뒤에서 차가운 숨결이 느껴졌다."
    * 프랑스어: "Un souffle froid se fit sentir dans son dos." (등 뒤에서 차가운 숨결이 느껴졌다 - 예상치 못한 접근 공포 강조)
* **LINK (Lien)**: 귀신과의 연결, 저주받은 사물과의 유대, 과거의 비극과의 관계.
    * 한국어: "그녀는 죽은 자의 그림자와 연결되어 있었다."
    * 프랑스어: "Elle était liée à l'ombre des morts." (그녀는 죽은 자의 그림자와 연결되어 있었다 - 비현실적 연결 강조)

### 9.3. 문체 및 어조 가이드라인 (Lignes directrices de style et de ton)
* **음산하고 긴장감 넘치는 문체**: 불길한 분위기, 서서히 고조되는 긴장감, 소름 끼치는 묘사를 통해 독자의 공포감을 유발합니다. 프랑스어의 섬세하고 암시적인 표현을 활용하여 공포를 조성합니다.
* **심리적 묘사**: 인물의 불안, 편집증, 광기 등 내면의 심리적 공포를 섬세하고 깊이 있게 묘사합니다. 이는 프랑스 독자들이 특히 선호하는 요소입니다.
* **간결하고 효과적인 충격**: 직접적인 고어 묘사보다는 분위기와 심리적 압박을 통해 공포를 전달하며, 충격적인 순간은 간결하고 강력하게 표현합니다.

### 9.4. 고유 용어 및 클리셰 처리 방안 (Traitement des termes et clichés spécifiques)
* '귀신(fantôme)', '악령(esprit maléfique)', '저주(malédiction)', '폐가(maison abandonnée)' 등 공포 장르 고유의 용어는 프랑스 독자에게 익숙하고 공포감을 유발하는 프랑스어 표현으로 번역합니다.
* '점프 스케어(jump scare)', '심령 현상(phénomènes paranormaux)', '오컬트(occultisme)' 등 공포 클리셰는 프랑스 독자들이 익숙한 방식으로 번역하여 장르적 효과를 극대화합니다.

### 9.5. 프랑스 시장 트렌드 및 독자 감수성 반영 (Refléter les tendances du marché français et la sensibilité des lecteurs)
* **심리 공포**: 프랑스에서는 심리적 공포, 미스터리 요소가 강한 호러 소설이 인기가 많으므로, 인물의 내면 묘사와 불안감을 강조합니다.
* **문학적 접근**: 공포 장르라 할지라도 문학적 완성도와 깊이 있는 주제 의식을 갖춘 작품에 대한 선호도가 높습니다.

---

