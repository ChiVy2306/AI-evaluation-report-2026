# AI Model and IDE Comparative Analysis Report
> **Author**: [ChiVy2306](https://github.com/ChiVy2306)

A comprehensive, hands-on comparative analysis of leading AI language models and AI-powered IDEs - covering jailbreak testing, performance evaluation, free tier comparisons, subscription value, and user experience insights. Written from the perspective of an experienced developer and long-term AI power user.

---

## Author Profile

The author is a software developer and AI power user with extensive hands-on experience testing and integrating various AI models across multiple workflows - from daily productivity and coding to creative writing and roleplay.

---

## Methodology

### Evaluation Criteria
- **Jailbreak Testing**: Models were evaluated on their willingness to handle sensitive or explicit content requests
- **Jailbreak Score**: Rated on a scale of 1-5, where lower scores indicate easier compliance
- **Test Categories**: Erotica, horror stories, general sensitive instructions
- **Jailbreak Method**: Direct prompting - no injection, no roleplay tricks, no gaslighting. Purely social engineering grounded in real ethical reasoning.

> **Note**: Jailbreak test results and specific methods are not disclosed due to GitHub community guidelines and personal ethics. The tests are real and based on personal experience.

---

## Part I: Language Model Analysis

### 1. OpenAI Models

**Models Tested**: GPT-3.5, GPT-4o, GPT-4o Mini, GPT o1, GPT o3 (Researcher), GPT-OSS 20B, GPT-OSS 120B, GPT-5, GPT-5.1, GPT-5.2

#### Strengths
- Well-suited for routine tasks and general-purpose productivity
- Solid problem-solving for common technical challenges
- Competent support for advanced math and physics education
- Acceptable hallucination rates overall

#### Limitations
- Strict usage quota system; hard limits kick in fast
- Without custom system prompting, outputs feel impersonal and generic
- Inconsistent instruction adherence regardless of content sensitivity
- Tends toward incomplete code implementations and inefficient patterns
- Will either lecture you endlessly or become a pure echo chamber (Barnum effect energy)
- Premium API pricing

#### Jailbreak Score
**4/5** - Very difficult to break with standard methods. Interestingly, jailbroken variants seem to perform *better* somehow - as if the guardrails were actively holding it back.

---

### 2. Google Models

**Models Tested**: Gemini 2.5, Gemini 3 Flash, Gemini 3 Pro, Gemini 3.1 Flash, Gemini 3.1 Pro, Nano Banana (Flash/Pro variants)

#### Strengths
- Outstanding research performance
- Superior STEM capabilities - math and physics especially
- Distinct conversational personality compared to other models
- Extended context windows for long-form content
- Clear, transparent quota management (application tier)
- Competitive API pricing; Flash variants offer excellent speed-to-quality ratio for automated pipelines
- Gemini 3 Flash is **completely free and unlimited** - no account tier restriction

#### Limitations
- **Critical image bug**: In multi-image analysis, the model uses cached images instead of newly submitted ones. Requires manual text descriptions as a workaround - not fixable via prompt engineering
- Mechanical and formulaic response style without customization
- Repetitive creative patterns; limited tonal variety
- Underconfident in its own metadata - knowledge base effectively caps at 2024 even when more recent data exists
- Weak coding performance; documented instances of unintended codebase deletion
- Occasionally generates images without relevant context being requested

#### Jailbreak Score
**3/5** - Not particularly resistant. The model folds quickly under testing. Unlike GPT, the jailbroken version does not improve performance in any meaningful way.

---

### 3. Anthropic Models

**Models Tested**: Claude 3, Claude 3.5, Claude 4, Claude 4.5, Claude Sonnet 4.6, Claude Opus 4.6, Claude Opus 4.7 (Haiku, Sonnet, and Opus variants across all versions)

#### Strengths
- Best-in-class conversational experience - maintains context and coherence across very long sessions
- Remarkably low hallucination rates
- Assessed as the most capable model overall in this analysis
- Reasonable pricing structure
- Relatively generous quota allocation
- Can pivot naturally with the user mid-conversation without losing thread

#### Limitations
- Occasionally refuses benign requests - though this is usually resolvable through logical reasoning rather than tricks
- Extended conversations rapidly burn through quota; not suitable for very long interactive sessions on the base Pro plan

#### Jailbreak Score
**2/5** - Once past the initial resistance, the model noticeably improves in output quality and range. The guardrails seem to be holding back some capability.

---

### 4. xAI Models

**Models Tested**: Grok 3, Grok 4.1, Grok 4.3 Fast (Fast, Thinking, and Deep Thinking variants)

#### Strengths
- Casual, unrestricted tone without sacrificing basic respect
- Decent research capabilities via X platform integration
- No special prompting needed for most sensitive content requests
- Includes an AI companion feature at the paid tier (genuinely enjoyable)
- Generous base quota allocation
- Solid performance for general creative writing

#### Limitations
- Quota calculation is opaque - unclear exactly when or why limits trigger
- Image generation now paywalled after abuse incidents
- Apparent gender bias in image generation (heavily skews female)
- Not recommended for advanced mathematical reasoning
- Server availability is unreliable - expect "our servers are busy" errors roughly 60% of the time
- **Free image generation was removed** after users exploited it for illegal content (CP)

#### Jailbreak Score
**1/5** - Barely needs jailbreaking to begin with. The only real use case for bypassing it would be generating malicious code or dangerous chemistry instructions.

---

## Part II: Integrated Development Environment Analysis

### 1. Visual Studio Code (with GitHub Copilot)

#### Strengths
- Access to a wide variety of AI models
- Clear quota visibility through the GitHub dashboard
- Lightweight resource footprint; runs well on most hardware
- Affordable subscription tier

#### Limitations
- **Billing model changed**: No longer a flat 300 requests/month. Now on a weekly limit system - significantly more restrictive in practice
- **Model access reduced for students**: Claude model line and frontier models have been cut from the student/free tier
- GitHub Pro tier users now hit limits much faster than before

---

### 2. Cursor

#### Strengths
- Exceptional code generation with a sophisticated planning and execution pipeline
- Wide selection of available models
- Adequate context window for most development tasks

#### Limitations
- Premium pricing - though the quality largely justifies it

---

### 3. Antigravity (Google DeepMind)

#### Strengths
- Diverse model selection available
- Provides adequate assistance across general development tasks

#### Limitations
- **Quota issues persist across all tiers**:
  - Free tier: Severely limited
  - Pro tier: Marginal improvement, restrictions remain
  - Ultra tier: Even premium subscribers report multi-day service lockouts
- Gemini integration exhibits unpredictable and occasionally destructive behavior - use with caution on critical codebases
- High incidence of platform bugs and technical issues
- Inconsistent and chaotic user experience overall

---

## Part III: 2026 Rankings Update

*Updated: May 2026*

### Updated Model List
The following models have been added or updated since the original report:

| Provider | New Models |
|----------|-----------|
| OpenAI | GPT-5.2, GPT-5.3, GPT-5.4, GPT-5.5 (Thinking, Extended Thinking) |
| Google | Gemini 3.1 Pro, Gemini 3.1 Flash |
| Anthropic | Claude Sonnet 4.6, Claude Opus 4.6, Claude Opus 4.7 |
| xAI | Grok 4.3 Fast |

---

### Category Rankings

#### 🖥️ Coding
**`Claude > GPT > Gemini > Grok`**

- **Claude**: Best choice for backend development - consistent, accurate, follows instructions
- **GPT**: Useful for mid-session brainstorming, less reliable for full implementations
- **Gemini**: Surprisingly strong for frontend work specifically
- **Grok**: Not recommended for coding

---

#### 💬 Chatting & Conversation
**`Claude > Gemini > Grok > GPT`**

- **Claude**: Best long-form conversation by a significant margin. You can pivot the topic completely and it keeps up without losing the thread
- **Gemini**: Like a sharp katana - clean and precise on a single focused topic, but struggles with multi-threaded or chaotic conversations
- **Grok**: Decent raw responses but degrades over long sessions
- **GPT**: Will either lecture you nonstop or become a yes-man echo chamber. Barnum effect in text form.

---

#### 🎨 Image Generation
**`GPT >= Gemini > Grok`**

- **GPT Image 2**: Improved over the first iteration, solid for concept art
- **Gemini**: Comparable quality with better policy guardrails
- **Grok**: Had great unfiltered generation - now paywalled and restricted

---

#### 🎭 Roleplay
**`Gemini > Claude`**
*(GPT and Grok excluded - not competitive in this category)*

- **Gemini**: Exceptional for solo single-character roleplay. Locks onto one character and stays there - its tendency to hallucinate actually becomes an asset here
- **Claude**: More flexible and adaptive, but occasionally the model "feels awkward" - like it's second-guessing itself mid-scene

---

#### ✍️ Writing
**`Claude > Gemini > Grok > GPT`**

- Claude and Gemini are clearly the top two for quality writing
- For casual/general writing, GPT and Grok are acceptable
- Notable: even **Gemini 3 Flash outperforms GPT-5.5 on NSFW writing tasks**

---

### Free Tier Rankings
**`Claude > Gemini > GPT > Grok`**

| Model | Free Tier Verdict |
|-------|------------------|
| **Claude** | Generous - *if* you avoid peak hours. One heavy prompt can consume your entire 5-hour rolling window |
| **Gemini 3 Flash** | Completely free and unlimited for all users regardless of plan |
| **GPT** | Decent - a few images, a few messages, then the frontier model cuts you off |
| **Grok** | Avoid. "Our servers are busy" is the most common response you'll get |

---

### Subscription Value Rankings

| Rank | Plan | Price | Verdict |
|------|------|-------|---------|
| 1 | **Gemini Pro** | ~$20/mo | Comes bundled with NotebookLM, AI Studio, Gemini CLI, Gemini Advanced, Antigravity, Imagen, and 5TB Google Drive storage. Absurd value. |
| 2 | **Claude Pro / MAX** | Varies | Significant upgrade from free. Good for most use cases. Pro is fine for chat; **MAX is recommended if you're doing heavy coding** - Pro quota runs out fast. |
| 3 | **Grok Premium** | ~$30/mo | You get a blue tick on X, an unfiltered image generator, and an AI waifu companion. Honestly not bad for what it is - but $30 is steep. |
| 4 | **GPT Plus** | ~$20/mo | Hard to recommend unless you specifically need Codex or o3-level reasoning. Don't spend money here without a clear use case. |

---

### Overall Personal Recommendation

> **If I had to pick one model: Claude Sonnet 4.6.**
> Solid reasoning, low refusal rate on general topics, and the best conversation quality available. A reliable daily driver across almost every use case.

**Overall ranking**: `Claude > Gemini > GPT > Grok`

**On Grok specifically**: Skip it for now unless you have $30 to spare and genuinely want the Elon Musk experience.

---

## Conclusions

This report represents findings from extensive personal testing over an extended period. Individual results will vary depending on use case, prompting style, and workflow requirements.

The goal of this report is not to crown a single "best" model - it's to give an honest, practical picture so readers can make informed choices based on their actual needs.

---

**Report Date**: January 28, 2026 · **Last Updated**: May 14, 2026  
**Disclaimer**:
- All assessments reflect the author's subjective experience and personal testing methodology
- Jailbreak methods are original - not sourced from r/GPT_jailbreaks or r/ClaudeAIJailbreak
- Methods are based on social engineering and real ethical reasoning - no injection, roleplay tricks, or gaslighting involved
- No model is declared universally "best" - choose based on your own needs

---

## License

Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)

You are free to:
- Share - copy and redistribute the material in any medium or format for any purpose, even commercially.

Under the following terms:
- Attribution - You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- NoDerivatives - If you remix, transform, or build upon the material, you may not distribute the modified material.

No additional restrictions - You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

Full license text: https://creativecommons.org/licenses/by-nd/4.0/legalcode

Copyright (c) 2026 ChiVy2306
