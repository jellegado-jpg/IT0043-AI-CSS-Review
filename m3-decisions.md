# Module 3 Design Tokens & AI Evaluation

## 1. Design Tokens Explanation
- `--color-primary` (`#1d4ed8`): Primary brand color for buttons and active link states.
- `--color-bg` (`#f8fafc`): Light grey background reducing screen glare.
- `--color-text` (`#1e293b`): High-contrast body text fulfilling WCAG AA (~15.5:1).
- `--space-md` (`1rem`): Centralized spacing token maintaining visual rhythm.

---

## 2. Refined Evaluation Criteria

### Rule Count & Selector Complexity
- **Rule Blocks**: Grouped selectors (e.g., `h1, h2, h3`) count as one rule block since they share a single declaration block.
- **Selector Complexity**: Measured as the specificity chain (total simple selectors, descendant relationships, and pseudo-classes).

### Token Architecture
- Described as a **Comprehensive Token-First Architecture**, acknowledging that universal primitives (`#ffffff` button text) are applied directly where appropriate.

---

## 3. AI Comparison Evaluation

### Why `css/style.css` was Selected
1. **Maintainability**: Centralized `:root` custom properties allow instant global updates across all 4 HTML pages.
2. **Accessibility**: Includes explicit `:focus-visible` states to support full keyboard navigation compliance.
3. **Responsive Scaling**: Avoids fixed side padding that consumes screen area on 320px viewports.

---

## 4. AI Use Disclosure Statement
ChatGPT was used to generate an alternative dark-mode stylesheet (`ai-style.css`) from raw HTML markup and participate in technical critique. All contrast checks, viewport tests, and final code edits in `css/style.css` were performed independently.

I can explain every line of this submission without assistance.
