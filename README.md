# Webscripting-webpage
**Prompt:**  
“Help me style a personal webpage using CSS variables, cards, and responsive grid layout.”

**LLM Response (excerpt):**  
Suggested using `:root` design tokens, CSS Grid with auto-fit and minmax, and hover effects for cards.

**My Changes:**    
- Combined duplicate `.card` styles into a single block.  
- Fixed incorrect variable names (e.g., `--accent` → `--color-accent`).  
- Improved contrast for CTA button text.

## Design Notes (Tokens)

 `--color-bg` -Page background color 
 
`--color-surface` -Card/section background 

`--color-text`- Default body text 

`--color-muted` -Secondary text color 

`--color-accent` -Accent color for headings/buttons 

`--font-base` -Base font family 

`--font-heading` -Heading font family 

 `--radius` - Border radius 
 
`--gap` -Grid gap spacing 

`--shadow` - Card box-shadow style 

## Accessibility Notes

- **Contrast checks:** Verified text vs background contrast meets WCAG AA using WebAIM Contrast Checker 
- **Focus visibility:** Clear outline styles added for keyboard focus.  
- **Responsive layout:** Tested at ~375px width — no horizontal scroll and readable content.

## Timebox

**Total time spent:** ~4 hours (rounded)
