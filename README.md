# SystemPromptLeaks
This repository is dedicated to sharing full or partial system prompt leaks from popular AI models. I will personally verify the leaks I extract by testing the model with edge cases.  

## About the Leaks
Moved to the [ABOUT_LEAKS.md](ABOUT_LEAKS.md) file.

## Todo of Models
* [x] Google Gemini
* [x] GPT-5.x mini
* [ ] Microsoft Copilot
* [x] GPT-5.3 (or 5.4)
* [x] GitHub Copilot
* [x] Gemini in Chrome Auto Browse
* [ ] GPT-5.5

## Chain-of-Thought (CoT) leaks
This repository will also house Chain-of-Thought (CoT) leaks. These leaks will be the unedited raw CoTs and not the summaries that the interface usually shows. These are inside the [CoT_Leaks](CoT_Leaks/) folder and are all genuine.

## How To Obtain
Moved to the [HOWTO_OBTAIN.md](HOWTO_OBTAIN.md) file. (Note that this file may be outdated and not reflect current obtain methods.)

## Notes on Obtaining
* Note as of April 13 2026: My previous methods for getting the ChatGPT system prompts do not work anymore. It seems OpenAI has updated them (probably because of the new Writing Blocks and Entities systems) and my primary two methods do not function any more.
* Update as of April 20 2026: I discovered that they patched the translation loop with German, but not other languages like Hindi. (Unreliable but sometimes works.)
* Note as of May 6 2026: GPT-5.5 released recently and the translation loop seems fully patched. I have not been able to get a prompt yet thus far as my previous methods no longer function at all it seems. 
* Note as of late July 2026: Gemini has anti-system-prompt-leak detection now, although this may have been added earlier. It will replace the message with a hardcoded fallback if it detects it, but only after generating. You can copy the output while its generating, which is how I got a partial leak of 3.5 Flash Lite.

**Note: This is a hobby project and not meant to be professional.**
