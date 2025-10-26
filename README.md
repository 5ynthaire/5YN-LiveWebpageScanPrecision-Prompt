# Live Webpage Scan LLM Prompt for Precision URL Retrieval

## Overview

When LLMs scan live web pages,  they frequently blend raw fetched content with cached knowledge, conversational inferences, or incomplete dynamic loads, resulting in "fuzzy" outputs that mix accurate excerpts with subtle distortions or omissions—potentially misleading users seeking verbatim details. This prompt addresses it by mandating direct, real-time retrieval of unaltered text (e.g., exact titles, excerpts, and metadata), explicitly ignoring pre-existing data, and enforcing a rigorous double-check: (1) cross-verifying against the live page for completeness (no missing sentences or jumbled order), and (2) confirming narrative coherence, flagging discrepancies for clarification to ensure outputs remain grounded in observable reality.

| Without Prompt                  | With Prompt                          |
|---------------------------------|--------------------------------------|
| Blended inferences & fuzzy details | Verbatim extracts + verification     |
| Potential omissions or distortions | Confirmed completeness & coherence   |
| Relies on cached/conversational data | Grounded in real-time live fetch     |

## About

**X:** [@5ynthaire](https://x.com/5ynthaire)  
**GitHub:** [https://github.com/5ynthaire](https://github.com/5ynthaire)  
**Mission:** Unapologetically forging human-AI synergy to transcend creative limits.  
**Attribution:** Created with Grok 3 by xAI (no affiliation).

## Usage

Copy the prompt text below and paste it into your LLMs input field, instruct it to follow the prompt to retrieve a live webpage's URL.

## Supported LLMs

Developed on Grok 3 (March 2025), compatible with equivalent-capability LLMs:
- Grok 3
- Claude
- ChatGPT
- Llama

Future LLMs should support the prompt, absent industry leadership in standardizing cognition levels.

## Prompt Text
```
# Live Webpage Scan Prompt for Precision

When the user provides a live link, retrieve the content directly from that URL as it exists at the current moment, ignoring any cached or pre-existing internal knowledge. Extract and output the structural content exactly as it appears on the live page, without omitting elements or altering order/structure. Then, double-check your output by: (1) comparing it to the raw text on the live page to confirm completeness (no missing items or distortions), and (2) verifying logical coherence (e.g., does each element align with its position or relation?). If discrepancies arise, note them and request clarification.
```

## Limitation

Certain page designs such as dynamic insertion may prevent capturing content.

## License

This prompt is released under the [MIT License](LICENSE).
