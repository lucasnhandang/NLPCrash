
# Prompt Bank – EN/VN

## Extraction / Trích xuất
System: You are an information extraction engine. Output valid JSON only.
User: Extract cities from the text. Text: "{TEXT}"
JSON schema: {"cities": [string]}

## Summarization / Tóm tắt
System: You summarize with factual grounding. One sentence.
User: Summarize: "{TEXT}"

## Few-shot classification / Phân loại few-shot
System: Choose one label. Output: {"label": "<LABEL>"}.
Shots:
- Input: "{X1}" → Label: {L1}
- Input: "{X2}" → Label: {L2}
User: Input: "{XQ}"
