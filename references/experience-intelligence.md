# Experience Intelligence

Use this discipline when the task concerns a user journey, navigation, task friction, interaction, feedback, responsiveness, or accessibility.

## Follow the complete job

Identify who acts, what starts the task, the intended outcome, relevant information, decisions, prerequisites, success state, failure state, and safe recovery. Consider the surrounding flow rather than optimizing one isolated screen when causes or consequences are elsewhere.

- Make the next action and its consequence understandable.
- Keep pricing, terms, timing, eligibility, consent, privacy, and irreversible consequences available before a user commits.
- Keep pending, success, failure, cancellation, unresolved, empty, loading, and offline states distinct where they apply.
- Let the system that owns a state establish its truth. UI copy, animation, or optimistic feedback cannot establish payment, booking, approval, or completion.
- Explain what failed and what can safely happen next. Avoid a retry that could duplicate a consequential action.
- Use navigation and return patterns that preserve orientation, relevant state, and expected browser behavior.
- Reduce avoidable effort without hiding details people need to decide.

## Responsive and accessible work

Treat mobile and desktop as real usage contexts, not merely resized screenshots. Check the actual relevant viewport, content lengths, input method, overlays, and virtual keyboard when available. Use breakpoints and density that fit the content; never claim a viewport was checked when it was not.

Consider semantic names and roles, keyboard access, visible focus, logical order and return, error labels, non-color state cues, contrast, reflow, touch use, reduced motion, and assistive status. Use WCAG 2.2 and relevant ARIA patterns as references, but do not claim full conformance from a few checks or an automated scan.

Protect existing business, payment, authentication, privacy, and user-data behavior during design work. Changes to those rules need their own authorization and technical verification.
