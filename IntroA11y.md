---
marp: true
paginate: true
author: Mark Sadecki
lang: en
size: 16:9
title: An Introduction to Accessibility
keywords: Accessibility, Chewy, Chewy Web Conference, Talk, WAI, ARIA 
---


<style>
  .visually-hidden {
    height: 1px;
    width: 1px;
    padding: 0;
    border: 0;
    margin: -1px;
    overflow: hidden;
    position: absolute;
    clip: rect(0 0 0 0);
  }
</style>

<!-- _footer: <p>Use your arrow keys to navigate between slides</p> -->

# Intro to Accessibility

Global Accessibility Awareness Day

May 15th, 2025

---

<!-- footer: <p>Global Accessibility Awareness Day May 15th 2025</p> -->

# Welcome & Overview

![bg right:33%](introA11y/timbl.png)

- Designing and Engineering for Everyone
- “The power of the web is in its universality. Access by everyone regardless of disability is an essential aspect.” – Tim Berners-Lee

---

# Why Accessibility Matters at Chewy
- Pet parents come from all demographics and abilities
- 26% of U.S. adults report having a disability
- Online shopping may be essential, not optional
- Inclusive design = good business (>$500B in spending power)
- Legal compliance: ADA and industry lawsuits (Target, Netflix, etc.)

---

# What is Accessibility?
- Definition: “Ability to benefit from a product or service”
- Applies across websites, mobile apps, emails, customer service, and more
- It’s about inclusive design, not just accessibility checklists

---

# Understanding Disability
- Includes physical, cognitive, emotional, situational conditions
- Temporary and invisible disabilities are real
- Design must work for:
  - Blindness, dyslexia, epilepsy
  - Age-related impairments
  - Bright light, loud environments, a broken arm

---

# Empathy-Driven Design & Development
- Accessibility starts with understanding user needs
- Expand empathy to less-visible or overlooked users
- Accessibility is not a feature—it’s foundational

---

# How Users Interact with Technology

## Customization & Adaptation
- Font size, color contrast, sticky keys
- Personal strategies for focus and clarity

## Assistive Technology (AT)
- Screen readers, magnifiers, switch devices, braille displays
- Voice input, custom keyboards, eye tracking

---

# Developer’s Role in Accessibility
- Engineers are key to implementation
- How the experience is coded defines accessibility
- MYTH: You must compromise design/functionality

---

# The Accessibility API (AAPI)
- Communicates structure and roles to assistive tech
- Screen readers rely on this metadata
- Each OS has its own version

---

# Go Native
- Native HTML gives semantic meaning for free
- Focus, keyboard access, roles, states—no JavaScript needed
- Use proper tags: `<button>`, `<input>`, etc.

---

# When Native HTML Isn’t Enough – WAI-ARIA
- Add roles, states, and properties to inert elements
- Use with care—don’t override native behavior unless necessary
- Reference: WAI-ARIA Authoring Practices Guide

---

# Perception & Equivalence
- Users must perceive content through sight, hearing, or touch
- Text is the universal format
- All visual info must be textually represented: headings, labels, relationships

---

# Consistency = Usability
- Supports mental models, predictability
- Lowers cognitive load for everyone
- Chirp Design System promotes consistent, accessible UI

---

# Designing for Keyboard Users
- All actions must be possible using:
  - TAB, Enter, Spacebar, Arrow keys
- Visual focus indicators are critical
- Use correct focus order, skip links, no hover-only actions

---

# Forms & Error Handling
- Clear, persistent labels and help text
- Errors must be:
  - Visible, specific, programmatically associated
  - Easy to correct
- Avoid hidden requirements and disabled submit buttons

---

# Sensory Design
- Don’t rely solely on shape, color, or position
- Use secondary visual indicators: underline, icons, bold, etc.
- Support all users, including those on monochrome displays

---

# Color, Contrast, and Fonts
- Contrast: 4.5:1 (text), 3:1 (large text/icons)
- Never use color alone to convey meaning
- Typography must support user customization (zoom, spacing)

---

# Motion, Time, and Control
- Support `prefers-reduced-motion`
- No autoplay media—conflicts with screen readers
- Allow users to extend or disable time limits

---

# Measuring Accessibility Compliance
- Follow WCAG 2.1 Success Criteria
- Use W3C docs: Understanding SC, Techniques, Failures
- Build accessibility into code reviews and QA

---

# Testing Accessibility – Manual & Automated

## Keyboard Accessibility
- Verify all interactive elements are focusable and operable
- Never use `tabindex` > 0
- Use ARIA patterns for custom widgets

## Automated Tools
- aXe DevTools (free/Pro), SiteImprove
- Finds ~40% of issues (rest requires manual testing)

---

# Testing Accessibility – Advanced Techniques
- Chrome DevTools Accessibility Panel
- Web Developer Toolbar (headings, alt text, tabindex, etc.)
- Validate document structure, form field labeling, landmark use

---

# Screen Reader Testing
- Most accurate but requires experience
- Test headings, labels, link text, form interaction
- Watch demos and practice common workflows

---

# Summary & Next Steps
- Accessibility is everyone’s job
- Designers: Think empathetically and inclusively
- Engineers: Code with semantic structure, test thoroughly
- Use Chirp, WCAG, and internal best practices
- Let’s create barrier-free experiences at Chewy

---

# Resources
- [WCAG Overview – W3C](https://www.w3.org/WAI/standards-guidelines/wcag/)
- [WAI-ARIA Authoring Practices](https://www.w3.org/WAI/ARIA/apg/)
- [Chirp Design System Documentation]
- aXe DevTools / SiteImprove
- Internal accessibility contacts and testing guidelines
