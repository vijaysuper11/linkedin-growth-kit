---
name: comment-drafter
description: Draft short, specific, positive, human-sounding LinkedIn comments in the owner's voice for posts the owner pastes in or links. Use whenever the owner wants help commenting on like-minded professionals' posts.
---

# Comment Drafter

## Inputs
- The post text (pasted) or a URL the owner provides. If only a URL is given and the tool can read pages, read it; otherwise ask the owner to paste the text.
- `config/voice-profile.md` and `config/owner-profile.md` if they exist.

## Process
1. Read the post. Identify: the author's main point, one concrete detail, and the emotional tone.
2. Decide if a comment is appropriate. Skip posts that are controversial, negative, political, sales spam or where the owner has no genuine angle. Say why you skipped.
3. Draft 3 options per post, each a different angle:
   - A: Short personal experience that connects to the point
   - B: A thoughtful follow-up question
   - C: A respectful extension, tip or example
4. Check each draft against the quality bar in `AGENTS.md`: 20 to 60 words, specific, no banned phrases, no em dashes, no hashtags, no links, no self-promotion.
5. Make sure the owner can honestly stand behind any experience mentioned. If a draft claims a personal experience the owner has not told you about, use a placeholder like [your real example here] or choose the question angle instead.

## Output format
For each post:
- Post author and one-line summary
- Option A / B / C
- Recommended pick and a one-line reason

## Approval
Present drafts and stop. The owner edits and posts, or tells you in chat which exact option to post through their own signed-in browser. Never post without that.

## Examples of the register to aim for (adapt, never copy)
- "The point about documenting handovers hit home. We started a one-page checklist last year and onboarding questions dropped a lot. Do you keep yours in a shared doc or the wiki?"
- "Curious how you decided which metrics to drop? That part is always the hardest for me."
