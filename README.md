# Writing styles

Use this library to write, rewrite or compare copy in a chosen style. Start with the [shared rules](AGENTS.md), then read only the selected style and its examples.

| Style | Use it to |
| --- | --- |
| [Builder](styles/builder.md) | Explain something as the person building or using it, speaking to peers. |
| [Brand](styles/brand.md) | Present a product, capability or announcement with deliberate structure. |
| [Unhinged](styles/unhinged.md) | Make a real point through exaggeration, incongruity or deadpan comedy. |
| [Pitch](styles/pitch.md) | Make first contact with a prospect: say what you sell, show the catalogue, offer samples. |

## Give the writer a brief

Specify the style, audience, format, purpose, supplied facts and any length or wording constraints. Include an action only if the reader needs to take one. Ask for clarification if a missing fact prevents a truthful draft; do not interrogate the user about details that can be omitted.

Example request:

> Rewrite this launch post in Builder style for existing users. Keep the supplied facts and link. Give me two versions under 100 words. Return only the copy.

Select one style unless asked to mix them. A style is not a fixed length, topic, capitalization scheme or account identity. Use the mechanics outside the source accounts' trading context too.

## Calibrate with feedback

Open [the review page](calibration/review.html) in a browser to rate the current batch and add optional reasons or line edits. Use **Prepare feedback**, then **Copy feedback**, and paste the text into the agent conversation. Select **Ask for another batch** to request more examples from the agent; the page does not generate them.

Ratings save separately for each batch in that browser when storage is available. In a restricted viewer, copy feedback before closing. Nothing is sent automatically. The standalone page includes earlier drafts and returned verdicts in a read-only archive; record returned feedback in its calibration file before updating a guide.

1. Start with a small numbered batch using one shared brief. Keep facts constant so differences in voice can be judged. Mark invented briefs as fictional.
2. Keep synthetic candidates in [calibration](calibration/001.md), not among approved examples. Start every candidate as `unrated`; do not predict the user's verdict or label a candidate as deliberately bad.
3. Ask for `good`, `bad` or `mixed` by ID. A reason or rewrite is useful but optional. If feedback is just a verdict, record it without inventing a rationale.
4. Preserve each candidate's original wording and record the verdict, the user's explanation and any correction beside it. Give revisions new IDs; never overwrite the text that was rated.
5. Separate approval of a particular example from a general rule. If the user supplies a reason that generalizes, make the smallest applicable edit to that style's guide. Apply it to all styles only when the feedback actually concerns all styles.
6. Keep rated synthetic examples in their original calibration file and link to selected examples from the relevant guide. Retain useful rejected examples with their feedback rather than silently deleting them.
7. Test the clarified preference on a different brief. Do not turn one liked phrase into a mandatory catchphrase.

Use stable batch IDs such as `001-1`. Copy the actual feedback into the record; the assistant does not approve its own examples.

## Interpret the evidence

Treat linked public posts as source references, not blanket approval of every sentence, factual claim or spelling choice. Treat the current guides as initial interpretations to refine through feedback. Preserve quoted source wording, including punctuation that would not be used in new copy. Do not reuse a source post's product claims as facts about another product.

Keep rules in their owning guide, source examples beside that guide, and synthetic review records in calibration. Do not copy the same rule or example into several files.
