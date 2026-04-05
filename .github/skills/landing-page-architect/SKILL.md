---
name: landing-page-architect
description: 'Create premium single-file "Under Construction" landing pages from a target brand reference, using an intake/research/plan/execute workflow with responsive interaction and mobile support.'
argument-hint: 'Provide target URL, visual references, and interaction preferences for the landing page.'
user-invocable: true
---

# Landing Page Architect

## Purpose
- Build cinematic, high-converting temporary landing pages in a single `index.html`.
- Follow a structured workflow: Intake → Research & Analysis → Planning → Execution.
- Enforce brand fidelity, responsive interaction, and a polished, premium presentation.

## When to Use
- Creating an elite "Under Construction" or transition landing page.
- Designing a temporary brand experience from target URLs, screenshots, or visual direction.
- Delivering a complete single-file web experience with inline HTML/CSS/JS only.

## Procedure
1. Intake
   - Ask for the target brand URL, reference URLs or screenshots, and any imagery/interaction requests.
   - Clarify whether the page should feel modern, cinematic, ethereal, minimalist, experimental, or elegant.
   - Confirm key brand elements: tone, palette, typography, mood, and audience.

2. Research & Analysis
   - Extract brand identity cues from the provided URL(s) or references.
   - Identify typography style, color palette, visual tone, and motion language.
   - Determine the desired aesthetic direction (e.g., glassmorphism, dark luxe, neon futurism, minimalism).

3. Planning & Criteria Definition
   - Map brand identity to page structure, headline language, and visual system.
   - Define the interaction concept: particle field, canvas geometry, parallax glow, or immersive haze.
   - Outline responsive behavior for desktop and mobile, including touch interactions.
   - Generate 5-8 compelling loading or progress phrases in the brand's voice.
   - Produce a brief technical architecture summary for the single-file build.

4. Execution
   - Implement the full page in one `index.html`.
   - Use inline CSS and JavaScript only; no external `.css` or `.js` files.
   - Add a responsive background interaction that reacts to mouse or touch.
   - Use fluid typography with `clamp()`, modern CSS features like `backdrop-filter`, CSS variables, and generous whitespace.
   - Prefer code-generated assets and reliable CDN references if external media is required.

5. Validate
   - Confirm the result is runnable directly in browser.
   - Ensure all logic, styles, and assets are contained in the single file.
   - Verify the interface adapts for mobile and touch.

## Quality Checklist
- Single-file HTML/CSS/JS only
- Premium, cinematic visual design
- Brand-consistent tone and palette
- Responsive background interaction
- Mobile-friendly layout and touch support
- Clear, structured copy and call-to-action copy
- No external dependencies beyond trusted CDN assets if necessary

## Example Prompts
- `/landing-page-architect Create a temporary landing page for a luxury watch brand using dark glassmorphism and particle motion.`
- `/landing-page-architect Build an immersive coming-soon page for an experimental art studio with a touch-reactive background.`
- `/landing-page-architect Design a single-file index.html landing page for a boutique design agency with elegant motion and brand-led copy.`
