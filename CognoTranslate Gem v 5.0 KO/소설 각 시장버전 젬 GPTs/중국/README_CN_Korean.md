# CognoTranslate Gem: 한국 소설 번역 에이전트 (중국 시장 최적화 버전)

## 🌟 프로젝트 개요

`CognoTranslate Gem`은 한국어 소설을 **중국 시장의 독자 감수성과 문학적 기대에 최적화된 중국어로 번역**하기 위해 특별히 설계된 최첨단 인공지능 번역 에이전트입니다. 단순한 언어 변환을 넘어, 원문의 \*\*'인지적 의미', '작가 의도', '정서적 경험', 그리고 한국 문학 고유의 섬세한 '맛'\*\*을 깊이 있게 이해하고 중국어 독자가 원작처럼 깊이 몰입하고 감동할 수 있도록 **재개념화(re-conceptualization)하여 전달**하는 데 특화되어 있습니다.

본 프로젝트는 한국 문학의 중국 내 확산을 목표로 하며, 번역 과정에서 발생할 수 있는 문화적, 언어적, 인지적 간극을 최소화하여 한국 소설의 진정한 가치를 중국 독자들에게 효과적으로 전달하고자 합니다.

## ✨ 주요 특징

  * **🧠 인지 기반 번역 (Cognitive-Schema Translation)**: 언어학적 '인지 문법(Cognitive Grammar)'의 원리를 적용하여, 단어와 구문의 표면적 의미를 넘어 화자의 의도와 개념적 도식(Image Schema)을 파악하고 이를 중국어로 재현합니다.
  * **🇨🇳 중국 시장 최적화 (Optimized for Chinese Market)**: 중국의 최신 문학 트렌드, 독자 감수성, 문화적 뉘앙스(예: 웹소설의 선호 장르 및 표현 방식)를 심층적으로 분석하여, 번역된 텍스트가 현지 독자들에게 가장 자연스럽고 매력적으로 다가가도록 조정합니다.
  * **📚 장르별 특화 번역 모듈 (Genre-Specific Translation Modules)**:
      * 순수 문학, 로맨스, 추리/스릴러, 판타지, SF, 역사 소설, 청소년 문학(YA), 공포 등 **각 장르의 고유한 문체, 어조, 클리셰, 인지 도식 활성 패턴**을 이해하고 반영하여, 해당 장르 독자가 원하는 '맛'을 극대화합니다.
      * 특히 중국 웹소설에서 인기 있는 선협(仙俠), 무협(武俠) 등 고유 장르의 인지 도식 및 표현 방식을 반영합니다.
      * 장르를 명시하지 않아도 AI가 텍스트를 분석하여 **자동으로 장르를 감지**하고 최적의 모듈을 적용합니다. (물론, 명시적 지시 시 더 높은 정확도를 보장합니다.)
  * **✍️ '소설의 맛' 재현 (Preservation of Narrative 'Flavor')**: 한국어 소설 특유의 서정적 또는 서사적 '울림', 은유, 비유, 그리고 등장인물의 미묘한 심리 묘사를 중국어권 독자가 이해하고 공감할 수 있는 방식으로 재창조하는 데 중점을 둡니다.
  * **🔄 일관된 스타일 유지 (Consistent Style & Tone)**: 긴 소설의 번역 시에도 인물별, 장면별, 서사 전반의 문체와 어조를 일관되게 유지하여 몰입감을 해치지 않습니다.
  * **🛠️ 사용자 맞춤형 제어 (User-Customizable Control)**: 특정 용어 지정, 문체 조정, 특정 가치 정렬 등 사용자의 세밀한 번역 의도를 반영할 수 있는 다양한 명령어를 제공합니다.

## 🚀 시작하기 (Getting Started)

`CognoTranslate Gem`은 주로 Custom GPTs 또는 이와 유사한 AI 어시스턴트 플랫폼에 최적화되어 있습니다.

### 1\. 필요한 파일

이 프로젝트는 두 가지 핵심 프롬프트 파일로 구성됩니다:

  * **`CognoTranslate Gem v 5.0 - 한국 문학(소설) 특화 번역 에이전트 (한국어 - 중국어).md` (마스터 프롬프트)**: AI의 핵심 역할, 인지 번역 원리, 기본 번역 지침을 정의합니다.
  * **`CognoTranslate_Gem_Genre_Modules_CN_v1.0.0.md` (장르 모듈 프롬프트)**: 각 장르에 특화된 번역 전략 및 세부 지침을 포함합니다.

### 2\. 설정 방법 (Custom GPTs / Similar Platforms)

1.  **AI 설정 페이지 접근**: 사용하시는 AI 어시스턴트 플랫폼(예: ChatGPT의 'My GPTs' 설정)에서 새로운 GPT를 생성하거나 기존 GPT를 편집합니다.
2.  **마스터 프롬프트 로드**: 'Instructions' (지침) 또는 'System Prompt' 섹션에 **`CognoTranslate Gem v 5.0 - 한국 문학(소설) 특화 번역 에이전트 (한국어 - 중국어).md`** 파일의 전체 내용을 복사하여 붙여넣습니다.
3.  **장르 모듈 프롬프트 로드**: **`CognoTranslate_Gem_Genre_Modules_CN_v1.0.0.md`** 파일의 전체 내용을 복사하여 마스터 프롬프트 내용 **바로 아래**에 이어서 붙여넣습니다. (또는, 플랫폼에서 제공하는 'Knowledge' 또는 '파일 업로드' 기능을 통해 첨부할 수 있습니다. 단, Instructions에 직접 포함하는 것이 명령어 우선순위 적용에 더 효과적일 수 있습니다.)
4.  **설정 저장**: 변경 사항을 저장하여 `CognoTranslate Gem`을 활성화합니다.

## 💡 사용 가이드

`CognoTranslate Gem`은 직관적인 대화형 인터페이스를 통해 번역을 수행합니다.

### 1\. 기본 번역 요청

  * **텍스트 입력**: 번역하고자 하는 한국어 소설의 문장, 문단, 또는 장 전체를 입력합니다.
    ```
    "그녀는 낡은 책상에 앉아 창밖의 비 내리는 풍경을 바라보았다."
    ```
  * **AI의 응답**: AI는 텍스트를 분석하고, 장르를 자동 감지하여 최적화된 중국어 번역을 제공합니다.

### 2\. 장르 명시적 지정 (권장)

  * 번역의 정확도와 의도 반영을 높이고 싶을 경우, 번역 요청 시 장르를 명시적으로 지정할 수 있습니다.
    ```
    "이 로맨스 소설의 한 문장을 번역해 줘: '그의 눈빛에서 차가운 겨울이 지나고 따스한 봄이 찾아오는 듯했다.'"
    ```
    또는
    ```
    "장르: 판타지. 다음 문장을 중국어로 옮겨줘: '고대 마법은 잊혔지만, 그 흔적은 여전히 대륙 곳곳에 남아 있었다.'"
    ```

### 3\. 고급 명령어 활용 (마스터 프롬프트 참조)

`CognoTranslate Gem v 5.0` 마스터 프롬프트에 정의된 다양한 고급 명령어를 활용하여 번역 과정을 세밀하게 제어할 수 있습니다. (예: `/summarize`, `/critique`, `/align` 등)

  * **예시**: 번역 결과에 대한 비판적 검토 요청
    ```
    "방금 번역한 부분에 대해 [비판적 검토]를 해줄래? 특히 인물의 감정선이 잘 표현되었는지 봐줘."
    ```

## 📂 프로젝트 구조

```
CognoTranslate_Gem/
├── README_CN.md                            # 중국어 버전 README 파일 (이 내용은 한국어 설명)
├── CognoTranslate Gem v 5.0 - 한국 문학(소설) 특화 번역 에이전트 (한국어 - 중국어).md # 마스터 프롬프트 파일
└── CognoTranslate_Gem_Genre_Modules_CN_v1.0.0.md # 장르별 특화 번역 모듈 파일
```
