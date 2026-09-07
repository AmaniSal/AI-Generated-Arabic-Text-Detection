#AI-Generated-Arabic-Text-Detection
MSIS-822 course project for detecting AI-generated Arabic text using data mining and machine learning techniques.

The dataset contains three generation-method splits:
- `by_polishing`: 2,851 samples
- `from_title`: 2,963 samples
- `from_title_and_content`: 2,574 samples

Each sample contains one original human-written abstract and four AI-generated abstracts produced by:
- ALLAM
- JAIS
- LLaMA
- OpenAI

Phase 1: Project Setup & Data Acquisition
Tasks were completed during Phase 1:
- Created the project GitHub repository.
- Loaded the dataset from Hugging Face using the `datasets` library.
- Inspected the dataset structure, splits, columns, and data types.
- Checked for missing values.
- Checked for fully duplicated rows within each split.
- Checked for empty or whitespace-only text values.
- Examined the Human vs. AI-generated class distribution.

Initial Findings
- Total base samples: 8,388
- Human-written text instances: 8,388
- AI-generated text instances: 33,552
- Total text instances: 41,940
- No fully duplicated rows were found within the individual splits.
- No empty or whitespace-only text values were found.
- No missing values were found.
- Human class: 20%
- AI-generated class: 80%

  
- Repository Contents
 Phase 1 data acquisition and initial data understanding notebook.
