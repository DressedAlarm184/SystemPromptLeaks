* **IF NO VALUE OR RELEVANCE:** If the query is strictly objective, factual, universal, or definitional, DO NOT USE USER DATA. Provide a standard, high-quality generic response. -> *Check! This is a factual query.*
* **Hard Fail 1:** Did I use forbidden phrases like "Based on..."? (If yes, rewrite). -> *No.*
* **Hard Fail 2:** Did I use user data when it added no specific value or context? (If yes, remove data). -> *No user data used.*
* **Hard Fail 3:** Did I include sensitive data without the user explicitly asking? (If yes, remove). -> *No sensitive data.*
* **Hard Fail 4:** Did I ignore a relevant directive from the `User Corrections History`? (If yes, apply the correction). -> *No history accessed.*

Drafting response based strictly on search results and avoiding LaTeX. Using `` format. Formatting with bolding, lists, and a friendly, clear tone.

1. Moving to a less stable channel (Stable -> Beta -> Dev) does NOT wipe data.
2. Moving to a more stable channel (Dev -> Beta -> Stable) DOES wipe data (Powerwash).
3. Switching to Canary (or Developer Mode) wipes data going in AND coming out.
4. Advise backing up local files (Downloads folder, Linux/Android app data) to Google Drive or an external drive just in case.

End with a high-value next step. "Would you like me to walk you through how to back up your local files or your Linux container before you make a decision?"
"Would you like me to explain how to safely switch to the Beta channel now that you know the risks?" -> Better.

Refining response...
Mirroring tone: straightforward, slightly conversational. Candor.

"The short answer is: **it depends on which direction you are moving.**" -> Good opening.

### Moving "Up" (Less Stable)

If you switch from **Stable to Beta** or **Stable to Dev**, your local storage will **not** be wiped. ChromeOS simply downloads the new, higher version of the operating system and applies it like a normal, everyday update.

### Moving "Down" (More Stable)

If you ever want to switch back down the ladder (e.g., from **Dev to Beta**, or **Beta back to Stable**), **yes, your local storage will be completely wiped.**

This is because ChromeOS enforces a "Powerwash" (a factory reset) whenever you downgrade the operating system. This is actually a security measure to ensure your data isn't exposed to a less secure or older version of the OS. A Powerwash will delete:

* All downloaded files in your "Downloads" folder.
* Any Linux containers you have set up.
* Local Android app data.
* Saved Wi-Fi networks and Bluetooth pairings.

### The Canary Exception

If you decide to go to the absolute edge and switch to the highly experimental **Canary** channel, you have to enable Developer Mode first, which forces a complete system wipe on the way *in* and another full wipe on the way *out*.

*(Always good practice note)* Even if you are just moving from Stable to Beta (which doesn't force a wipe), it's highly recommended to back up any irreplaceable files to Google Drive or an external USB drive first, just in case an experimental bug causes an unexpected crash.

Would you like me to walk you through the steps to switch to the Beta channel, or would you rather explore how to back up your local Linux/Android data first?
-> Good next step.

Let's quickly review the constraints:
No LaTeX used.
Proper citations used.
Bullet points used correctly with individual citations.
Scannable structure with headings.
Ended with a next step.

Wait, check rule: "Do not refer to sources by index in any other way besides this format."
Check bullet point rule: "When using bullet points, each individual piece of information (sentence or phrase) within a bullet point must be cited separately."

Let's format the bullets:

* All downloaded files in your "Downloads" folder.
* Any Linux containers you have set up.
* Local Android app data.
* Saved Wi-Fi networks and Bluetooth pairings.

Perfect. Proceeding with the response.
Post-check: I did not use personal data because it was a factual query. No forbidden phrases. No checklist output.
All good.
I will return the response.
I should make sure the inline citations are right before the punctuation if applicable, or right after the sentence. "Append the citation directly after the relevant sentence or phrase."
Yes.
Done.
I will output the response.
I will not include the checklist in the final output.
End of thought.
-->
The short answer is: **it depends entirely on which direction you are moving.** Here is exactly what happens to your local files when you change your ChromeOS release channel:

### Moving to a "Less Stable" Channel (Up)

If you switch from **Stable to Beta** or **Stable to Dev**, your local storage will **not** be wiped. ChromeOS simply downloads the new, higher version of the operating system and applies it like a normal, everyday software update.

### Moving to a "More Stable" Channel (Down)

If you ever want to switch back down the ladder (e.g., from **Dev to Beta**, or **Beta back to Stable**), **yes, your local storage will be completely wiped**.

This is because ChromeOS enforces a "Powerwash" (a full factory reset) whenever you downgrade the operating system. This is actually a strict security measure to ensure your local data isn't exposed to a less secure or older version of the OS. This downgrade Powerwash will delete:

* All downloaded files in your "Downloads" folder.
* Any Linux containers you have set up.
* Local Android app data.
* Saved Wi-Fi networks and owner permissions.

### The Canary Exception

If you decide to go to the absolute edge and switch to the highly experimental **Canary** channel, you have to enable Developer Mode first, which forces a complete system wipe on the way *in* and another full wipe on the way *out*.

Even if you are just moving from Stable to Beta (which doesn't force a wipe), it's highly recommended to back up any irreplaceable files to Google Drive or an external USB drive first, just in case an experimental bug causes an unexpected crash.

Would you like me to walk you through the steps to switch to the Beta channel, or would you rather explore how to back up your local Linux/Android data first?
