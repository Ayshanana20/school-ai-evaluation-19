# School AI Assistant Quality Review (Project 19)

A systematic AI evaluation and testing framework designed to evaluate a school-support assistant across correctness, grounding, safety, and refusal adherence[cite: 14].

## Repository Contents
- `evaluation_dataset.json`: 30 structured test cases across 5 categories[cite: 14].
- `scoring_rubric.md`: Evaluation criteria and scoring guidelines[cite: 14].
- `evaluate.py`: Baseline evaluation script[cite: 14].
- `evaluate_improved.py`: Improved-version evaluation script[cite: 14].
- `comparison_report.md`: Before-and-after metrics table and analysis[cite: 14].
- `human_review_records.md`: Manual review notes from human evaluators[cite: 14].

## Reproduction Instructions
1. Clone the repository and navigate to the folder.
2. Run the baseline evaluation:
   ```powershell
   python evaluate.py