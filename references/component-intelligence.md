# Component Intelligence

Use this discipline when selecting, composing, or refining a component or family of controls.

Inspect the current framework, design tokens, components, usage, and relevant states before creating something new. Reuse or extend a suitable pattern; keep purposeful differences when components serve different jobs. Do not require a design-system rewrite, new library, or framework migration to fix one control.

For each relevant component, establish its purpose, information hierarchy, semantics, variants, actual states, responsive behavior, accessibility needs, Design DNA, protected behavior, and verification. Consider buttons, forms, navigation, tabs, cards, menus, dialogs, sheets, status feedback, empty/loading/error states, and other patterns only as needed by the task.

## Composition and behavior

- Give the local decision a clear primary action unless the user genuinely has equal alternatives.
- Use a button for an action, a link for navigation, and the appropriate input or widget for a choice. Custom controls need the real keyboard behavior that their semantics imply.
- Preserve clear accessible names, labels, errors, visible focus, selected state beyond color alone, and safe hit areas.
- Include only state families the component actually has. Distinguish local visual state from async progress and authoritative domain state.
- Show pending and failure truthfully. Do not turn a click, spinner, icon, or optimistic label into proof of success.
- Keep essential content readable across relevant widths, long text, missing values, and realistic data. Avoid silent truncation.
- Use borders, shadows, cards, tags, dividers, and whitespace only when they support grouping, focus, scanning, contrast, or approved personality. Do not ban them by default.
- Give motion a user-facing purpose and honor reduced-motion preferences.
- Preserve existing component APIs and call sites during a narrow refinement; treat breaking changes as a separately scoped migration.

After an authorized implementation, check only the states and sibling instances that can be affected. A source or API review does not prove the component renders or behaves as intended.
