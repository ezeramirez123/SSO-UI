# Idea 7 — Two-Step Progressive Flow

A **two-step sign-in flow** — the pattern used by Google, Microsoft, and most modern SSOs.

**Step 1** — asks only for the Tufts username and shows a "Continue" button.  
**Step 2** — displays a username chip (with initial avatar and a "Change" link to go back), then asks for the password and shows the "Sign In" button.

This approach improves security (the password field only appears after the username is validated) and reduces visual clutter by showing one thing at a time. Steps slide in/out with a fade + translate transition via Alpine.

A service indicator at the top of the card persists across both steps, showing which app the user is signing into (swap the placeholder for a real logo or service name).

Built with **Tailwind CSS** + **Alpine.js** (both via CDN, no build step).
