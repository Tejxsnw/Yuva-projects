# Week 4: Enhancing Web Page Performance and Accessibility

## Objective
Optimize a static webpage for performance and accessibility while keeping the implementation simple, semantic, responsive, and maintainable.

## Improvements Implemented
- Semantic HTML5 landmarks: header, nav, main, section, article, aside, and footer.
- Skip-to-content link for keyboard and screen-reader users.
- Logical heading hierarchy and descriptive link text.
- Native form controls with explicit labels and validation.
- Visible :focus-visible styles for keyboard navigation.
- aria-live status feedback for the demo form.
- ARIA used only where it adds useful information.
- Responsive CSS using Grid, Flexbox, clamp(), relative sizing, and focused breakpoints.
- Reusable CSS custom properties and shared component rules to reduce duplication.
- No external frameworks, icon libraries, web fonts, or third-party scripts.
- Lightweight page structure and no large image/video assets.
- prefers-reduced-motion support for users who request less animation.

## Testing Approach
Test with browser Developer Tools at desktop, tablet, and mobile widths. Use Lighthouse for performance and accessibility audits, and WAVE or axe for additional accessibility checks. Keyboard testing should include Tab, Shift+Tab, Enter, and Space where relevant.

## Learning Outcome
The project demonstrates that performance and accessibility should be considered together. Semantic HTML provides built-in accessibility behavior, while a lean DOM and stylesheet reduce unnecessary work. The page is designed to remain usable without mouse interaction and to communicate structure clearly to assistive technologies.