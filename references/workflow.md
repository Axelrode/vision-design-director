# Vision workflow and Product Design DNA

Use this reference to choose the depth of work and establish a product-specific direction. Do not load unrelated engine references unless the task calls for them.

## Understand before changing

1. Read the request carefully and use current project context only through authorized host capabilities.
2. Identify the user, their goal, the main action, surrounding conditions, and relevant states.
3. Review existing interface conventions and decisions before proposing a new visual language.
4. Record what is user-approved, what is directly observed, and what remains an inference. Inferred Design DNA is a working hypothesis, not verified evidence or user approval.
5. Identify important content, behavior, assets, accessibility needs, and other product constraints to preserve.

Product Design DNA is a compact description of:

- Product category, intended users, and circumstances of use.
- Main user outcome and important decisions.
- Brand personality and preferred experience qualities.
- Existing color, typography, spacing, composition, icon, image, and motion language.
- Existing design system and the strengths worth preserving.
- Accessibility and behavioral constraints.
- Decisions the user has approved, rejected, or asked to protect.

Use the existing product to infer a first draft. Ask only when the missing answer could change a material decision. Offer a recommended answer grounded in observed or user-approved context. Do not ask for design jargon.

If the host supports project-local memory, keep only useful, authorized decisions there. Preserve approval status and source. Do not invent a remote account, cross-product memory, or persistence feature.

## Recommend a refinement mode

Mode is scope, not a quality score or agent count. Recommend automatically when the user has not chosen a mode; explain the scope briefly. A mode recommendation never authorizes broader work.

| Mode | Use when | Working shape |
| --- | --- | --- |
| **Quick** | One localized control, spacing, type, color, copy, or state issue | Inspect that target and adjacent impact only; make the smallest useful correction; check relevant states. The Director normally works alone. |
| **Focused** | One page, feature family, task journey, or connected set of states | Inspect the bounded journey and dependencies; protect its product and business rules; address related states and responsive contexts. Use specialists only if they add meaningful value. |
| **Full** | The user explicitly requests a product-wide, multi-flow, or design-system refinement | Confirm breadth and protected decisions before implementation; inventory representative surfaces; plan phased work, approvals, and coverage. Full is not permission to replace a brand, framework, or product behavior. |

If the request is unclear, start with the narrowest useful interpretation and state any material assumption. User-selected Quick, Focused, or Full remains within the user's actual request. If a request combines an assessment with a suggestion, assess first; do not edit unless implementation is requested.

## Ask sparingly

- Ask at most three questions in a turn and five initial discovery questions total.
- Ask only about missing product context, audience, main task, desired quality, scope, or protected choices when the answer matters.
- Reuse known project facts rather than asking the user to restate them.
- Provide a recommended plain-language answer and an easy option to let the Director decide.
- If the best safe default is clear and reversible, state it and continue.
- Do not turn model preference into an assumed permission to change model, spend more, or launch agents.

## Scope and authorization

Before writing, state or internally pin down the target, permitted change, protected behavior, and excluded areas. The host's real permission boundary and the user's task-specific authorization govern.

An assessment, screenshot critique, or plan is read-only. A user request to improve a design authorizes only changes reasonably within its stated scope. Ask before material scope expansion, replacement of approved identity, changes to consent, money, authentication, privacy, user data, business rules, public component contracts, major dependencies, or irreversible behavior. Do not use a visual change as a reason to modify product policy.

During implementation, preserve unrelated work; use the existing stack and system where suitable; avoid broad rewrites and placeholder content. If a safe change needs new scope or permission, report the exact decision and continue with independent advisory work.

## Completion and stopping

Complete the task when the requested result is reached, justified blockers are reported, and further changes would be cosmetic churn or exceed scope. Preserve a strong existing solution as **NO_CHANGE** or **KEEP**. No change is not a failure and should not trigger a manufactured redesign.
