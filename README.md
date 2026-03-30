# SystemPromptLeaks
This repo contains full or nearly full leaks of system prompts from AI models. The only system prompts contained here are the real system prompts. I will verify them by testing the models before uploading them here.

## About the Leaks
* ``GPT-5miniInstructions03-25-26.txt`` contains the full system prompt for ChatGPT under the GPT-5 mini model. I have not obtained the prompt for GPT-5.3 or similar non-mini models.
* ``GeminiInstructions03-25-26.txt`` contains the overview of Google Gemini system instructions. I do not believe these change between selected model. This was obtained using the Fast option in the UI. As I would discover a few days later, this was not the full leak, only around half of it.
* ``GeminiSystemPrompt_FULL_VERSION_033026.txt`` contains the comprenshive full system prompt for Gemini. It contains everything the previous one had, along with special new instructions I had never seen before.

## Todo of Models
* [x] Google Gemini
* [x] GPT-5 mini
* [ ] Microsoft Copilot
* [ ] GPT-5.3 (or 5.4)
* [ ] GitHub Copilot

## Chain-of-Thought (CoT) leaks
Chain-of-Thought (CoT) leaks will be documented in a seperate folder inside the repo. CoT leaks will be the raw CoT, and not the summarized version that the UI typically shows. The filename will contain the model and usually date.
