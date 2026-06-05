# Idea 8 — React, Component-Based Two-Step

A **React 18** rewrite of the two-step flow, demonstrating how the design would be structured in a real React application. The UI is broken into reusable components — `<ServiceIndicator />`, `<Field />` (with `forwardRef` for programmatic focus), `<Btn />` — and state is managed with `useState` hooks.

Step transitions use **directional CSS keyframe animations**: advancing slides in from the right; going back slides in from the left. Changing React's `key` prop on the step container causes a remount, which replays the animation. Errors trigger a shake via the same key-change technique. Built with **React 18** + **Babel Standalone** + **Tailwind CSS**, all via CDN — no build step required.
