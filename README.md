# Teammate Stack — a template

A *teammate stack* is a small set of plain-text files that tell an AI collaborator who you are, how you sound, how you want to be worked with, and what it's allowed to touch. You write it once, point the AI at it at the start of every session, and stop re-explaining yourself.

This repository is the template: eight numbered files plus an audit log, each with guidance on what goes in it and de-identified worked examples showing what a filled-in version looks like. The examples come from a real stack that has been in use for a couple of months; the person has been removed and the method kept.

## The files

| File | What it holds | How often it changes |
|---|---|---|
| `01-identity.md` | Who you are, what you're trying to do, what you value, the collaborator you want | Rarely — months |
| `02-voice.md` | How you sound when you write well, built from quoted evidence | Rarely |
| `03-anti-style.md` | What the AI must never sound like; your own tells | Slowly, as evidence accumulates |
| `04-context.md` | What matters *right now* — priorities, live questions, constraints | Often — refresh when work changes |
| `05-rules.md` | Standing instructions for how the AI collaborates with you | Settles by experience |
| `06-opening-move.md` | The one-sentence openers that start each kind of session | Rarely |
| `07-connectors.md` | What the AI may read, what it may write to, which tools are in, fenced, deferred, or out | When tools change |
| `08-leverage.md` | What's automated, what's watched, what's queued — and the rule for climbing | Each audit |
| `AUDIT-LOG.md` | Dated record of when the stack was built and each time it was reviewed | Quarterly |

The numbering is the reading order. An AI told to "read the stack first" reads 01 through 08; 04 is the one it should weight most heavily for *what to do today*, and 05 for *how to do it*.

## How to build yours

The method that produced the original is **pre-draft, then interview.** Don't start from a blank page — that produces the self-description problem, where you write down how you'd like to sound rather than how you do.

1. **Gather evidence.** Existing notes, things you've written and are proud of, a CV (even a stale one), any persistent memory your AI tool already holds about you. Ask two or three people who read your writing what it sounds like, and what habits of yours they'd want caught.
2. **Have the AI pre-draft each file from the evidence.** It will be wrong in instructive ways. The wrongness is the interview material.
3. **Interview yourself against the draft.** File by file, correct what's wrong and — more importantly — notice what the AI *couldn't* have known. Those are the lines that matter most.
4. **Leave the open questions open.** `05-rules.md` has a section for things that will only settle by experience. Don't force them.
5. **Date it and schedule the first audit.** Three months out. The audit checklist is in `AUDIT-LOG.md`.

Expect the first version to take an afternoon and to be about seventy percent right. The remaining thirty percent arrives in the first few weeks of use, mostly through `05-rules.md` — every time the AI does something that annoys you, ask whether a rule would have prevented it, and if so, write the rule.

## How to use it

At the start of a session, point the AI at the folder and use an opener from `06-opening-move.md`. If your AI tool has persistent memory, have that memory *point to* the stack rather than duplicate it — the stack is the canonical home; memory is a cache.

Some principles the worked examples encode, which you may or may not share:

- **The AI sharpens the thinking; it does not do the thinking.** Synthesis that happens in the AI's fingers doesn't compound in your head.
- **Critique before compliment.** A compliment first is a tell that the critique has been softened.
- **Act by default; ask only when the answer would change the output**, when the consequence is irreversible, or when two reasonable readings diverge.
- **A tool earns entry only if it reduces an inbox.** Deferred tools stay deferred until they prove this.
- **Build just-in-time.** The leverage ladder in `08-leverage.md` — session → saved prompt → template → automation → compound — is climbed one rung at a time, and only when the next rung earns its complexity.

Delete any of these that aren't yours. A stack that says things you don't believe is worse than a shorter one.

## On private facts

Some facts about your situation — things you'd tell a close colleague but not a room — change how an AI should collaborate with you, and should never appear in anything it produces. `01-identity.md` has a fenced section for these, with a pattern: state the fact, state what it means for the AI in practice, state the fence. The resulting *behaviors* then become numbered rules in `05-rules.md`, phrased without the reason. The reason stays in 01.

If you ever share your stack, that section is the first thing to remove.

## Keeping two stacks

If you use AI at work and at home, keep two stacks and a firewall between them. General-purpose method (a pushback protocol, an ask-vs-act rule, the leverage ladder) can be ported from one to the other; identity, context, and anything specific to either world should not be. Record every port in `AUDIT-LOG.md`, including what you deliberately *didn't* port.

## License

CC BY 4.0 — see `LICENSE`. Adapt freely; keep the attribution.
