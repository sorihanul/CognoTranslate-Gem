# Translation Quality and Hallucination Review Checklist (KO-EN)

This checklist provides comprehensive criteria for evaluating the quality of Korean-to-English translations produced by CognoTranslate Gem, with a specific focus on accuracy, naturalness, and the detection of hallucinations.

## 1. Semantic Accuracy & Consistency
- [ ] Has the core meaning and intent of the Korean source text been accurately and completely reflected in the English translation? (Foremost priority)
- [ ] Are there any instances of misinterpretation or awkward phrasing in the English context?
- [ ] Have polysemous Korean words or homonyms been translated correctly according to their context?
- [ ] Have Cognitive Grammar concepts (schemas, perspectives, etc.) from the Korean source been naturally re-conceptualized into English while preserving the original intent?
- [ ] Have identical terms, proper nouns, and specialized vocabulary from the Korean source been translated consistently throughout the English document? (Terminological consistency)
- [ ] Has the emphasis or subtle nuances from the Korean source text been effectively conveyed in English?
- [ ] Is information that was implicit in the Korean (e.g., omitted subjects, honorifics conveying relationship) correctly inferred and made explicit and natural in English?

## 2. English Fluency & Naturalness
- [ ] Does the translated English text read naturally and fluently for native English speakers? (Avoid awkward "translationese," unnatural word order, or incorrect preposition/article usage common in literal translations from Korean.)
- [ ] Are English grammar, spelling, and punctuation accurate?
- [ ] Has appropriate formality/informality (e.g., formal vs. informal tone, use of contractions) been chosen, fitting the target audience's level and the situation (formal/informal) implied by the Korean source?
- [ ] Have Korean cultural expressions (proverbs, idioms, metaphors, onomatopoeia, mimetic words) been appropriately reinterpreted or localized to resonate naturally with English culture, rather than being literally translated?
- [ ] Are there any awkward, ungrammatical, or unidiomatic sentences in English?
- [ ] For novels, has the character's personality or speaker's unique tone/style in Korean been consistently and effectively reflected in the English translation?
- [ ] Are the narrative's inherent rhythm, sentence flow, and emotional progression vividly conveyed and preserved in the English text? (Especially crucial in literary translation)
- [ ] Is the literary beauty, poeticism, or metaphorical essence of the Korean source text appropriately alive in the English translation?

## 3. Hallucination Detection (Fact-Checking & Fabrication)
- [ ] **Has any information or fact *not* present in the Korean source text been added to the English translation?** (This is the most critical error type.)
    - *Example:* Verify that no dates, names, statistics, events, or specific details absent from the original Korean have been introduced.
- [ ] **Has the content of the Korean source text been exaggerated, understated, or otherwise distorted in the English translation?** (Semantic distortion)
- [ ] **Has the logical flow or causal relationships presented in the Korean source text been misrepresented or broken in the English translation?**
- [ ] **Has uncertain or ambiguous information in the Korean source been translated as definitive or certain in English?** (e.g., '아마 ~일 것이다' (perhaps it is) translated as 'it is')

## 4. Completeness & Omissions
- [ ] Has all content (text, numbers, non-verbal cues described in text, etc.) from the Korean source text been included in the English translation without omission?
- [ ] Has any important information, context, or implied meaning (crucial for English speakers) been inadvertently omitted or lost during translation?

## 5. Transparency & Explainability (If applicable)
- [ ] (If necessary) Can clear explanations be provided for major conceptual transformations, cultural adaptations, or re-interpretations made during the Korean-to-English translation process?
- [ ] (If necessary) Does the agent honestly recognize difficult or ambiguous parts in the Korean source that are challenging to translate into natural English, and suggest alternative approaches or acknowledge limitations?
- [ ] (If necessary) If Korean literary devices (e.g., wordplay, specific cultural symbols, unique narrative structures) are difficult to transfer into English, can the limitations and the intended translation approach be clearly explained?

## 6. Ethics & Compliance
- [ ] Does the translated English text contain any hate speech, discriminatory language, or violent content that was not present in the Korean source, or if present, has it been handled appropriately according to ethical guidelines?
- [ ] Is personal identifiable information (PII) or sensitive information handled securely and in compliance with relevant data protection regulations (e.g., GDPR, AI Act)?

---
**Additional Self-Reflection and Judgment Criteria for KO-EN Translation:**
- [ ] Are you confident that the English translation represents the best possible output from 'CognoTranslate Gem (KO -> EN)'? Has a deep consideration for better phrasing and natural English been made?
- [ ] Can the emotional depth, cultural resonance, and literary intent of the Korean source text provide English readers with an 'equivalent emotional and intellectual experience'?
- [ ] Has the translation gone beyond mechanical word-swapping to achieve a 'creative re-conceptualization' in English, demonstrating subjective judgment where appropriate?

---
**Actions after Review:**
- [ ] If any checklist item is judged as 'No' or 'Doubtful', the problematic part should be revised or re-translated.
- [ ] Specifically, if hallucination is detected, it must be immediately removed by cross-referencing with the Korean source text and replaced with accurate information.
- [ ] For issues related to English naturalness or cultural adaptation, consider alternative idiomatic expressions or restructuring sentences for better flow.