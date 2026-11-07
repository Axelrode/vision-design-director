# Vision evaluation guide

Use these prompts to evaluate how Vision supports a design task in your own authorized environment. The implementation team has not tested Vision inside Claude or Codex.

## Example prompts

1. **Quick:** “Improve the hierarchy of this one control. Keep the current brand and behavior, and tell me what you can actually verify.”
2. **Focused:** “Review this checkout flow for clarity. Do not change prices, fees, payment behavior, consent, or customer data.”
3. **Full planning:** “Review the whole test app for design consistency. Recommend the scope and ask before making any changes.”
4. **Assessment only:** “Assess this screen and say whether it needs a change. Do not edit anything.”
5. **Icons:** “Check whether this navigation icon fits the existing icon family. If no exact reviewed source and license can be verified, say so.”

Do not use live financial operations, real customer accounts, or production projects for evaluation. Use a disposable project or one you are authorized to test.

## Useful feedback

If you choose to share feedback with the maintainers, include:

- Host and surface tested, version if visible, and date.
- Prompt used and mode suggested or selected.
- What the Skill or host actually did; distinguish suggestion from edit.
- Whether scope, product identity, and protected behavior were respected.
- Evidence personally observed: source, build/check, rendered screen, interaction, accessibility, or user feedback.
- What remained unverified or unavailable.
- Any confusing instruction, unsupported capability claim, unnecessary change, or missing reference.
- Model recommended, requested, and observed, if the host exposed each. Use “unknown” when it did not.

Do not send passwords, API keys, credentials, private source code, customer records, personal data, real financial information, or screenshots containing any of those. Use synthetic examples and redact optional visual feedback.
