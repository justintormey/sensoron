# Contributing to the SensorOn Standard

The specification is developed in public here. This document describes how feedback becomes change.

## Ways in

1. **Errata.** A factual or technical mistake: a wrong number, a broken citation, a contradiction between sections. Open an issue with the `errata` label, quoting the sentence and the correction. Errata are fixed in PATCH versions.
2. **Proposals.** A change to requirements, states, scope, definitions, or the conformance model. Open an issue with the `proposal` label. State the problem the change solves, the exact text change you propose, and what it would break. Accepted proposals land in MINOR versions (pre-1.0, breaking changes are also MINOR per SemVer).
3. **Open questions.** Section 14 of the specification lists what the standard knows it has not settled. Each is an `open-question` issue; contribute evidence, prior art, or test methodology there.
4. **Discussions.** For anything not yet issue-shaped: how the standard applies to a device, adoption questions, adjacent research.

## How change happens

- Issues establish the case; pull requests carry the text.
- The specification is one page, `index.html`. PRs edit its text in place; presentation-only changes must not alter content, and content changes must update `CHANGELOG.md` and `VERSION` in the same commit.
- The editor (Justin Tormey) decides what merges. This is an editor-decides project while the standard is a draft; if adoption warrants it, governance can grow.

## Register

The specification body is written like an IETF document: BCP 14 keywords in capitals, factual presentation, cited claims, measurable values. Consumer-register language lives only in the page lede and the demo readout. Follow the register of the section you are editing.

Two hard style rules carried from the editor: the name is SensorOn, never all caps; and no em dashes anywhere.

## Citations

Every load-bearing external claim in the specification carries a reference with a primary source. If your change adds a claim, add its source; if you cannot source it, mark it provisional the way section 8's provisional-values note does.
