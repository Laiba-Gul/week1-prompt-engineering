# Prompt Basics — Zero-Shot vs Few-Shot

**Neurofive Solutions Internship · Week 1**

Compares zero-shot and few-shot prompting on a simple classification task: sorting customer-support messages into **Complaint**, **Question** or **Praise**. The same prompts were run on three LLMs.

## Results

| Model | Zero-shot accuracy | Few-shot accuracy |
|---|---|---|
| ChatGPT | 10/10 | 10/10 |
| Claude | 10/10 | 10/10 |
| Gemini | 10/10 | 10/10 |

**Key finding:** accuracy was identical, but few-shot prompts produced more structured and consistent output — Claude and Gemini in particular followed the requested format more closely when given examples. Few-shot prompting mainly reduces ambiguity in output format on simple tasks.

## Repository contents
| File | Description |
|---|---|
| [`prompts.md`](prompts.md) | The zero-shot and few-shot prompts used |
| [`results.md`](results.md) | Model outputs for each message |
| [`comparison.md`](comparison.md) | Accuracy table and observations |
| [`reflection.md`](reflection.md) | What I learned |
| `*.png` | Screenshots of each model's responses |

## Screenshots
| ChatGPT (zero-shot) | ChatGPT (few-shot) |
|---|---|
| ![ChatGPT zero-shot](chatgpt%20zero-%20shot.png) | ![ChatGPT few-shot](Chatgpt%20few-shot.png) |

| Claude (zero & few-shot) | Gemini (zero & few-shot) |
|---|---|
| ![Claude](claude%20zero-%20shot%20and%20few%20shot%20respectively%20.png) | ![Gemini](Gemini%20zero%20and%20few%20shot%20respectively%20.png) |
