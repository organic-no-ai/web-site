---
layout: custom
---

## So why this?

I expect a pretty serious backlash (hopefully not too disastrous consequences first, though maybe that'll sadly need to happen for the reconsideration to actually happen) against AI generated code.

_Maybe_ AI will get a lot better soon, but as of today (June 2025) it generates mostly garbage that _appears_ to mostly work... (for anything not completely trivial)

AI vibe coding is terrible and it will ruin an upcoming generation of new developers if we're not careful.

So anyway, at some point we'll need code that is guaranteed to have been hand crafted by a human, and this is what this sites wants to prepare for.

### But how?

How to find out a system or piece of code had no AI involved... is indeed very tricky. Maybe the author(s) solemnly swear it's the case? maybe some sort of licensing board for practitioners? audits?

I don't know... ideas welcome...

Some possibilities but kinda constraining:

- Process-based Proof (in addition to electronic signature of content, but humans are good at cheating)
    - Require creation tools to record edit history (keystrokes, diffs, timestamps).
	- Only accept content with continuous creation logs—like a time-lapse.
	- AI use shows up as copy-paste blobs or abrupt, large insertions.

- Restricted Environment with Attestation (a bit "much"... kinda worse than "no internet" allowed...)
	- Use a sandbox (like a signed Linux container or remote devbox):
	- No AI access (no internet or LLM API).
	- Actions are logged and attested.
	- System emits a signed proof: “This content was created in a cleanroom.”


### (Certified) Organic code - No AI involved stamp:

Would be nice to have something like this on some hand crafted software:

![Organic No AI stamp](organic-no-ai.png)

<!--
if you are a human designer and want to contribute a proper, no AI logo for this, please contact me (see github)
or l d email ly _at_ gmail
-->

### See also

<!-- local copy until origin is fixed, pending PR#1 -->
[Low Background Web](low-background) change 2018 to 2023 in that text.

[Dead Internet Theory](https://en.wikipedia.org/wiki/Dead_Internet_theory) (wikipedia) while the dates like 2016 makes this a consiparacy theory, sadly as of today, it may be true.
