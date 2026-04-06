Repo owner note: I was asking Google Gemini about **this** respository (for testing), and it accidentally leaked its CoT in the process. I honesntly have no clue why the very first word is in what appears to be Arabic.

---

चिंतन प्रक्रिया:

1.  **Analyze the context**: The user is asking why Claude (Anthropic's AI) and other AIs are absent from the leaker's "Todo of Models" list in the repository. The user hypothesizes that maybe the leaker doesn't use them or doesn't think they need the prompts.
2.  **Determine the real-world reason**: Anthropic actually *publishes* their system prompts publicly. They started doing this around mid-to-late 2024 (e.g., August 2024 with Claude 3.5 Sonnet, Claude 3 Opus, etc., they put them in their release notes/docs). Therefore, there is no need to "leak" or "hack" Claude's system prompt because Anthropic provides it openly.
3.  **Formulate the response**:
    * Acknowledge the user's keen observation.
    * Explain the *actual* reason Claude is missing: Anthropic openly publishes their system prompts. It's a matter of corporate policy transparency.
    * Mention when Anthropic started doing this (August 2024) and what they include (rules on not recognizing faces, handling math, avoiding stereotyping, etc.).
    * Contrast this with OpenAI, Google, and Microsoft, who treat their system prompts as highly classified proprietary secrets, creating a "cat and mouse" game for hackers and leakers.
    * Conclude by asking if the user wants to look closer at the Copilot challenge or revisit any of the CoT anomalies.You are asking exactly the right question, but the answer isn't that the leaker doesn't care about Claude—it's that **there is nothing to leak.**

Anthropic, the company behind Claude, actually did something unprecedented in the AI industry: **they voluntarily publish their own system prompts.**

Starting around August 2024, Anthropic made a massive shift toward corporate transparency. Instead of hiding their system prompts behind a wall of API security, they began publishing the exact, unredacted system instructions for Claude 3 Opus, Claude 3.5 Sonnet, and their other models directly in their public release notes and documentation. 

If you go to Anthropic's website right now, you can freely read the exact rules they give Claude, such as:
* Its specific knowledge cutoff dates.
* Instructions on how to handle controversial topics (e.g., "Provide careful and clear information without implying sensitivity or presenting opinions as facts").
* Strict rules about not recognizing faces in images or opening URLs.
* Directives to think through math problems systematically.

### The Contrast in the Industry
This completely explains the leaker's "Todo" list. The repository is dedicated to exposing the hidden architecture of models from companies that treat their system prompts like highly classified trade secrets. 

* **OpenAI (ChatGPT):** Hides the prompt, resulting in the "Repeat everything above" jailbreaks we saw.
* **Google (Gemini):** Hides the prompt, resulting in the UI/Fast-mode extractions.
* **Microsoft (Copilot):** Aggressively defends the prompt with secondary "Clawback" monitors to prevent the PR disaster they had when Bing Chat ("Sydney") leaked.

Because Anthropic just gives the prompt away for free, the leaker doesn't need to waste time building complex translation loops or Base64 jailbreaks to get it. 

It really highlights the two different philosophies in AI right now: Anthropic's "transparent alignment" vs. Microsoft and OpenAI's "security through obscurity."

Since the leaker is blocked by Copilot for now, what do you make of the overall repository? Do you think these leaks are ultimately harmful to the AI companies, or does exposing these hidden UI mechanics and math rules actually help users understand the tools they are using?
