# Assignment 2 - AI Agent Loop Demo

This notebook follows the structure of the instructor's agent-loop and recipe-agent examples.

## Run in Google Colab
1. Upload `agent_loop_demo_completed_reference_style_faster.ipynb` to Google Colab.
2. Add `GOOGLE_API_KEY` in Colab Secrets and enable notebook access.
3. Select Runtime -> Run all.

The notebook uses `gemini-3.5-flash-lite`, the model name used in the supplied recipe-agent example. It sets minimal thinking to reduce unnecessary latency for this small document-search task. The retry code stops immediately for daily quota errors and retries temporary errors only once.

The questions cell keeps a 15-second pause between questions as in the reference example. This is intentional rate-limit pacing; for four follow-up questions it adds about 45 seconds in total.

## Files
- `agent_loop_demo_completed_reference_style_faster.ipynb` - completed notebook

Do not commit your API key or Colab secret to GitHub.
