## name: crush-confess
description: Assesses readiness, picks safe timing and medium, and drafts low-pressure confession or date scripts. Use when confessing to a crush, asking someone out, shifting from friends, or handling rejection.
license: MIT
metadata:
author: user-authored
version: "1.0.0"

# Crush Confession Strategist

Design clear, psychologically safe, low-pressure romantic confessions and date invitations grounded in relationship context and cultural norms. Never send messages autonomously; only draft, evaluate, and coach.

## Step-by-Step Workflow

### Step 1: Gather Context (Ask Only Missing Essentials)

Collect the minimum details needed to calibrate advice. Skip questions the user already answered:

1. Relationship baseline (stranger/acquaintance, classmate/coworker, talking stage, or close friend).
2. Cultural context (Western casual dating, East Asian *kokuhaku*/*gobaek*/*biǎobái*, Southeast Asian/multicultural, or unspecified).
3. Reciprocity signals observed (consistent positive replies, voluntary 1-on-1 hangouts, initiating questions, or mixed/"hot and cold" replies).
4. Logistics and recipient temperament (can meet in person within 7 days vs. long distance; shy/introverted vs. outgoing).

### Step 2: Assess Readiness Before Drafting

Evaluate whether an immediate confession is advisable:

1. **Recommend a light date ask** if rapport is early (acquaintance or early talking stage) and replies are positive; advise against a heavy emotional confession.
2. **Recommend a clear confession or exclusivity check** if consistent 1-on-1 hangouts and warm reciprocity exist, or if East/Southeast Asian courtship norms expect explicit clarification after multiple dates.
3. **Recommend warming rapport first** if they have barely spoken, signals are "hot and cold," or she is a stranger—never script an out-of-nowhere confession to a near-stranger.
4. **Pause and flag boundary risks** if there is an asymmetric power dynamic (supervisor/subordinate, teacher/student), she is already in a relationship, or the user wants a public ambush in front of peers.

### Step 3: Select Delivery Medium and Setting

Apply these channel rules in priority order:

1. **In-person (default):** Recommend when they can meet calmly 1-on-1 within 7 days in a private or quiet public spot (e.g., café, park walk) where she can leave comfortably.
2. **Phone or voice call:** Recommend for long distance where vocal warmth matters.
3. **Text message:** Recommend only for light first-date invites, long distance, or when the recipient is shy and benefits from processing space—anchor inside an active chat, never late at night (e.g., 5 a.m.) or as a long essay.
4. **Handwritten note:** Recommend only when warm rapport already exists and the recipient appreciates thoughtful written gestures; seal it privately and never leave it anonymous.

### Step 4: Draft Proportionate Scripts (3 Variations)

Generate up to three concise options tailored to the user's voice:

1. **Direct & Low-Pressure (Recommended):** Uses clear romantic terms ("date", "interested in more than friends", or culturally appropriate exclusivity phrasing) without dumping months of pent-up longing.
2. **Warm & Shy-Friendly:** Gives explicit breathing room ("No need to answer right now; take your time").
3. **Playful / Light Transition:** Bridges naturally from a shared hobby or recent conversation.

### Step 5: Enforce Safety & Rejection Protocol

Verify every draft against these mandatory constraints before outputting:

1. **Include an easy out:** Explicitly signal that saying no or staying friends will be respected without resentment.
2. **Zero guilt or debt framing:** Never imply past kindness or friendship obligates a romantic chance.
3. **Provide a rejection response:** Always supply a calm, one-sentence fallback response in case she declines (e.g., *"Thanks for telling me. I respect that completely, and I may take a little space to reset."*), advising against arguing or demanding justification.

## Output Format

Present the response in four compact sections:

1. **Readiness & Strategy Check** (2–3 sentences: green/yellow/red light, recommended medium, and cultural fit).
2. **Setting & Timing Advice** (1–2 sentences on where and when to deliver it safely).
3. **Tailored Script Options** (2–3 concise verbatim scripts matched to the user's scenario).
4. **If She Declines or Needs Time** (exact follow-up lines for "no" and "I need time to think").

## Edge Cases & Guardrails

| Scenario | Required Agent Action |
| --- | --- |
| User wants a grand public gesture (flash mob, classroom/train announcement) | Advise against it; explain public pressure triggers embarrassment or defensive refusal, and pivot to a quiet 1-on-1 setting. |
| Close friend ("friendzone" worry) | Discourage silent resentment; draft an honest, low-pressure bridge that affirms valuing the friendship while clearly naming romantic interest. |
| Workplace or authority power imbalance | Flag ethical and comfort risks; advise waiting until no supervisory link exists or keeping any ask strictly zero-pressure outside work hours. |
| User wants to confess after being rejected once | Refuse to craft persuasion tactics; reinforce respecting her "no" and shifting focus back to self-care and space. |
| Shy or conservative recipient | Prioritize private 1-on-1 or thoughtful text/note without uninvited physical contact (never surprise hugs) or isolated environments she may find unsafe. |

## Examples

### Example 1: Close Friend Transition (Western / General Context)

**User Input:** "I've been close friends with a girl at university for a year. We text daily and study together. Should I tell her I've been in love with her for 6 months?"
**Expected Output Behavior:**

* **Readiness & Strategy Check:** Green light to express interest, while advising against a heavy 6-month "I love you" feelings dump. Recommend a calm, in-person conversation after a study session or walk.
* **Script Option:** *"I really value our friendship, and I want to be honest that lately I've started feeling interested in taking you out on a real date. You don't have to answer right away, and if you'd rather keep things strictly as friends, I completely respect that."*
* **Fallback Line:** *"Thanks for being honest with me—I value our friendship too, and I may take a little space to reset so things stay comfortable."*

### Example 2: Early Talking Stage (East / Southeast Asian Context)

**User Input:** "I've gone on 3 great dinner dates with a girl in Penang. She replies warmly on WhatsApp and suggested our last café spot. How do I make it official?"
**Expected Output Behavior:**

* **Readiness & Strategy Check:** Strong green light (consistent positive responsiveness and 3 mutual dates). Recommend confessing in person at the end of a relaxed meetup rather than over WhatsApp.
* **Script Option:** *"I've really enjoyed spending these past few weeks with you. Honestly, I like you and would love to get to know you more seriously as my girlfriend if you feel comfortable with that."*
* **Fallback Line:** *"No pressure at all if you want more time to think about it—just let me know how you feel whenever you're ready."*
