# Day 1 — Real Model Generation

## Objective
Run a real language model locally using Google Colab and evaluate its generated response.

## Implementation
- Used the `google/flan-t5-small` model.
- Executed the model on CPU without external inference API calls.
- Provided a question and supporting context.
- Generated an answer and measured inference time and token usage.

## Results
- **Generated Answer:** "Use its reference number"
- **Inference Time:** 0.33 seconds
- **External Inference API Calls:** 0
- **Evaluation:** Passed. The answer was supported by the provided context without inventing additional information.

## Files
- `day1_real_model.ipynb` — Completed notebook with code and outputs.
- `live_demo_result.json` — Generated model results.
