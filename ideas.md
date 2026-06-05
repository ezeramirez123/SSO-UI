# Tufts SSO Modernization

## Goal

Modernize the Tufts SSO login experience while maintaining Tufts branding, accessibility, trust, and simplicity.

The new design should feel like a modern university authentication portal rather than an IT administration system.

---

# Current Issues

## Branding

- Tufts branding feels secondary to the login form.
- Logo is disconnected from the authentication experience.
- Logo placement feels awkward and not visually centered.
- Users focus on the form rather than recognizing they are authenticating with Tufts.
- Compared to peer institutions (Harvard, MIT, Northeastern, Northwestern, Boston College), the experience feels less cohesive and less representative of the university.

## Visual Design

- Overall design feels outdated.
- Resembles an administrative portal.
- Heavy borders and dense UI.
- Excessive informational text.
- Visual hierarchy is weak.
- Service logos can become larger than the university identity.
- Blue gradient background feels dated.

## Mobile Experience

- Login card occupies too much vertical space.
- Layout does not scale consistently between desktop and mobile.
- Information density is too high for mobile devices.

## Content Problems

- References to Shibboleth are unnecessary for most users.
- Security warning text is visually dominant.
- Technical implementation details are exposed to end users.
- Too much support information appears before users complete login.

---

# Design Objectives

## Branding First

The user should immediately know:

> "I am signing into Tufts University."

Requirements:

- Larger Tufts logo.
- Stronger visual connection between logo and login form.
- Consistent Tufts identity across desktop and mobile.
- Branding should feel intentional but not overwhelming.

---

## Simplicity

Prioritize the primary action:

> Sign In

Requirements:

- Remove unnecessary text.
- Hide implementation details.
- Reduce cognitive load.
- Focus attention on authentication.

---

## Modern Visual Design

Requirements:

- Card-based layout.
- Clean typography.
- Increased whitespace.
- Softer visual treatment.
- Reduced borders and visual clutter.
- Contemporary university design language.

Avoid:

- Heavy gradients.
- Outdated portal styling.
- Dense layouts.
- Large blocks of instructional text.

---

## Mobile-First Design

Requirements:

- Responsive layout.
- Touch-friendly inputs.
- Comfortable spacing.
- Consistent visual hierarchy.
- Optimized for phone screens before desktop.

---

## Accessibility

Requirements:

- WCAG AA compliance minimum.
- Keyboard navigation.
- Screen reader support.
- Accessible color contrast.
- Clear focus states.
- Proper form labels.

---

# Content Strategy

## Keep

- Tufts logo
- Username field
- Password field
- Sign In button
- Forgot Password link
- Help/Support link

## Reduce

- Security warnings
- Technical explanations
- Authentication implementation details

## Remove If Possible

- Shibboleth-focused messaging
- Browser warning text
- Excessive support information

---

# Visual Direction

## Typography

- Proxima Nova
- Meta Serif where appropriate

## Colors

Primary:
- Tufts Blue

Secondary:
- Tufts Brown

UI:
- Digital Blue (#3172AE)

Avoid:
- Large blue gradients
- Multiple competing background colors

---

# Layout Recommendations

## Desktop

- Centered authentication card.
- Clear branding above or integrated into card.
- Strong visual hierarchy.
- Generous whitespace.

## Mobile

- Single-column layout.
- Large touch targets.
- Logo visible without scrolling.
- Form immediately accessible.

---

# Success Criteria

A successful redesign should:

1. Look unmistakably like Tufts.
2. Feel modern and professional.
3. Reduce cognitive load.
4. Improve mobile usability.
5. Improve accessibility.
6. Focus attention on signing in.
7. Remove unnecessary technical complexity.
8. Match or exceed peer university login experiences.
