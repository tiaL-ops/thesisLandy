# Thesis — Landy

## Folder Structure

### `data/`
- **`in_game_data/`** — Raw game logs: `gameEvents.csv`, `hints.csv`, `users.csv`
- **`learning_content/`** — Game learning content (`learn-content.json`)
- **`hints/`** — Extracted hints by modality: `read/`, `kinestethic/`, `aural/`, `visual/`
- **`evaluators_ratings/`** — Evaluator ratings (`ratings.xlsx`) and eevalutors separetely by language in json (`python.json`, `scratch.json`)
- **`llm_answers/`** — LLM responses for CS PCK questions (OpenAI, Anthropic, Gemini, Llama, Mistral, Qwen)

### `notebook/`
- **`EDA_Thesis_RQ1.ipynb`** — Exploratory analysis for RQ1, runs with `in_game_data/`
- **`EDA_Thesis_RQ2.ipynb`** — Exploratory analysis for RQ2, runs with `evaluators_ratings/` & `llm_answers/`







