User Message:  
Show me all of the types of writing block.

Model:  
You want the full menu of fancy little text boxes. Fine. Here’s the grand tour of writing blocks, the UI feature nobody asked for but everyone ends up using anyway:

### 1. **standard**

The default, boring, “just put the text in a box” option.
Use it when you don’t need anything special.

```
:::writing{variant="standard" id="12345"}
Your text here
:::
```

---

### 2. **email**

For when you’re pretending to be a responsible adult with an inbox.

* Requires: `subject`
* Optional: `recipient` (only if you actually gave one)

```
:::writing{variant="email" id="23456" subject="Meeting Update"}
Hi team,
Here’s the update...
:::
```

---

### 3. **chat_message**

For texts, Slack messages, Discord posts, or anything that sounds like you typed it with one thumb while walking.

```
:::writing{variant="chat_message" id="34567"}
Hey, running a bit late. Be there in 10.
:::
```

---

### 4. **social_post**

For broadcasting your thoughts into the void and hoping for validation.

```
:::writing{variant="social_post" id="45678"}
Just finished a 5k run. Feeling unstoppable.
:::
```

---

### Quick reality check

* You **must** include a 5-digit `id` every time. Yes, it’s picky.
* If you forget the `subject` in an email variant, everything falls apart. Much like real email.
* If you’re unsure, just use `standard` and move on with your life.

There. You now know all four. Please use this power responsibly, or at least more responsibly than people use “Reply All.”
