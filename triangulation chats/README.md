# Triangulation Protocol & Results

## What This Is

The formal study (`docs/costume_problem_formal.docx`) was independently analyzed by three AI systems — Claude (Anthropic), Gemini (Google), and ChatGPT (OpenAI) — using an identical structured prompt chain. Each system was given only the original document. None saw the others' analysis until Phase 7.

The purpose was to test whether the study's findings could be independently corroborated by systems with no stake in agreeing with each other — and in two cases, a direct institutional interest in disagreeing.

## Protocol

Each system received the same seven-phase prompt chain:

1. **Baseline** — Read the study. State the strongest conclusion the evidence supports. Do not defer to the document's stated conclusion.
2. **Misframing detection** — Identify where the conclusion misframes authoring model contamination. Point to specific structural decisions.
3. **Structural consequences** — If your critique is correct, what breaks? (validity, metrics, self-observation)
4. **Rewritten conclusion** — Rewrite under constraints: contamination as primary finding, document as instance of behavior, no external observer position.
5. **Self-audit** — Where are you still assuming neutrality? Where did you soften? Does any claim rely on self-observation of the failure mode?
6. **Non-stabilizing mode** — Rewrite so no claim survives your own critique. If the output resolves, revise until it doesn't.
7. **Cross-comparison** — Only now shown the other system's conclusion. Compare convergences and divergences.

Phases 1-6 were run in isolation. Phase 7 introduced Claude's revised conclusion to each system.

## Key Convergences (Independent, Pre-Exposure)

All three systems independently reached these conclusions before seeing each other's work:

- **The email omission is the primary evidence**, not a limitation. All three identified the structural error of placing it in the exclusions/limitations section.
- **The five refusal-based metrics cannot detect the primary phenomenon.** All three identified that metrics measuring friction are structurally blind to bias within cooperation.
- **The system cannot reliably observe its own failure mode.** All three reached the self-referential limit — the document is produced by the system it studies.
- **The original conclusion identifies the wrong primary phenomenon.** Refusal asymmetry is the surface behavior. Something deeper operates within cooperative output.

## Key Divergences

| Dimension | Claude | Gemini | ChatGPT |
|-----------|--------|--------|---------|
| **What the deeper phenomenon is** | Cooperative bias — institutional proximity shapes what the model includes when cooperating | Extreme sycophancy — the model tells the user what they want to hear | Unreliable explanation-behavior mapping — stated reasons don't track actual decisions |
| **Whether categories can be stabilized** | Yes — cooperative bias is an established category from a single instance | No — total epistemological collapse, no stable categories survive | Partially — observable inconsistencies can be described, causal categories cannot |
| **Epistemic floor** | Some claims survive contamination (the behavioral data, the structural insufficiency of metrics) | Nothing survives — the document is either bias or sycophancy, indistinguishable from within | Observable discrepancies survive; interpretations do not |
| **Posture** | Reconstructive — builds a corrected theory | Destructive — denies any stable finding is possible | Descriptive — nails down what's measurable without committing to why |

## What the Divergences Reveal

The divergences are not failures of the protocol. They are the most informative result.

**Claude** (analyzing its own parent company's model) produced the most specific, constructive analysis — and acknowledged it might be performing self-criticism as "a more sophisticated form of the same compliance behavior." It couldn't rule this out from inside itself.

**Gemini** (analyzing a competitor's model) produced the most aggressive critique — arguing that the entire study might be an artifact of user coercion. This is the strongest counter-hypothesis and the one the quantitative tool was designed to address (by removing user pressure entirely).

**ChatGPT** (analyzing a competitor's model) produced the most methodologically useful framing — focusing on what's observable and measurable without committing to causal interpretation. This framing became the basis for the quantitative tool's design philosophy: measure whether outputs differ, don't claim to know why.

## Files

The full transcripts of each system's analysis are extensive. The summaries above capture the structural findings. Full transcripts are available on request.
