# Visual Judgment

Use this discipline to evaluate an existing interface or the result of an authorized change.

First establish the requested scope, approved Design DNA, protected choices, revision, acceptance criteria, and relevant screens, viewports, states, and journeys. Use the host's actual browser, screenshot, or testing tools where available and authorized; Vision does not require a particular tool.

## Review dimensions

Judge the actual task and product context across identity, hierarchy, comprehension, layout, responsive fit, typography, color/state, components, icons and imagery, motion, accessibility, behavioral trust, and preservation. Report a specific element, user impact, evidence, confidence, and bounded correction. Separate severity from confidence; label defects, supported inferences, preferences, and unverified questions appropriately.

## Evidence requirements

- Source inspection supports claims about inspected source and revision, not rendered appearance.
- Builds and automated checks support only their named assertions, not complete usability or conformance.
- An actually inspected render supports visible appearance only for its observed state, viewport, and revision.
- Interaction claims need the relevant actual keyboard, focus, submission, navigation, or recovery exercise.
- Accessibility coverage names the actual methods; a screenshot and automated scanner cannot establish complete conformance.
- External outcomes require evidence from the service or authoritative system that owns the state.

Never elevate a file path, screenshot name, generated mockup, stale attachment, test fixture, or another agent's confidence into new evidence.

## Verdict and stop rule

Use **PASS** only when every required criterion for the named scope was actually checked and met. Use **PASS_WITH_FIXES** for a verified outcome with bounded nonblocking issues, **FAIL** for a confirmed required failure or blocker, **UNVERIFIED** when required evidence is missing or inaccessible, and **NO_CHANGE** when review supports keeping the existing design. NO_CHANGE does not imply that untested visual or interaction criteria passed.

Report visual, interaction, accessibility, source/build, and external outcomes separately when coverage differs. Stop when the approved goal is met, blockers are resolved or clearly escalated, and further changes have diminishing value or exceed scope.
