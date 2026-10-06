# R6 design research and decisions

Three research agents independently reviewed readability, motion, and engineering-review workflow with UI/UX Pro Max. Common recommendation: preserve the fixed all-pin physical connector map; make the selected relationship unmistakable and readable.

Implemented: paired magnified cavity neighbourhoods, labelled new-branch shelf, cache-backed hover with a cancelable 110 ms leave grace period, one brief endpoint emphasis, constant screen-space selected-wire thickness with white casing, selectable wire hit targets, structured electrical/evidence/checks inspection, circuit-name search, roving keyboard navigation, candidate knock-pair labels, and explicit reduced-motion CSS/JS handling. No electrical allocation changed.

The UIUX design-system searches leaned toward generic marketing/immersive themes. Those themes were not applied. The skill's precision, contrast, interaction, progressive disclosure and motion rules supplied the fallback design guidance.

Primary research references:
- KiCad net highlighting and net navigator: https://docs.kicad.org/9.0/en/eeschema/eeschema.html#net-highlighting
- Apple motion: https://developer.apple.com/design/human-interface-guidelines/motion ; verified official documentation JSON at https://developer.apple.com/tutorials/data/design/human-interface-guidelines/motion.json
- Apple colour: https://developer.apple.com/design/human-interface-guidelines/color
- SVG vector-effect: https://developer.mozilla.org/en-US/docs/Web/SVG/Reference/Attribute/vector-effect
- SVG pointer-events: https://developer.mozilla.org/en-US/docs/Web/SVG/Reference/Attribute/pointer-events
- Chrome animation guidance: https://web.dev/articles/animations-guide
- Web Animations cancellation: https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API/Using_the_Web_Animations_API
- W3C hover/focus content: https://www.w3.org/WAI/WCAG22/Understanding/content-on-hover-or-focus.html
- W3C interaction animation: https://www.w3.org/WAI/WCAG22/Understanding/animation-from-interactions.html

Map highlights are visual linkage, not measured electrical direction. HOLD/reserved paths remain distinct. B8/B9 are candidate sensor pair references; no grounded return was inferred. Original PDF remains preserved. Actual vehicle applicability and continuity remain unresolved.
