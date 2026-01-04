# Exploratory Testing Notes – Sauce Demo

## Session Overview
- Tester: Self-directed QA portfolio project
- Application: Sauce Demo
- Environment: Chrome / Windows 11
- Session Duration: 30 minutes

-----

## Areas Explored
- Login error handling
- Product sorting options
- Cart behaviour when adding/removing items
- Checkout navigation flow

-----

## Observations
- Login error messages appear quickly and are clear, but long messages may cause minor UI layout issues.
- Product sorting options function correctly and update the product list as expected.
- Cart updates immediately when items are added or removed, with no noticeable delay.
- Checkout flow is linear and prevents progression when required information is missing.

-----

## Issues Identified
- One low-severity UI issue identified where validation message text does not fit within its container on the login page (documented as BUG-01).

-----

## Questions for the Team
- Should validation messages be standardised across all error states?
- Is responsive behaviour for error messages consistent across browsers and screen sizes?

-----

## Suggested Areas for Further Testing
- Cross-browser testing (Firefox, Edge)
- Mobile and tablet responsive testing
- Accessibility testing (keyboard navigation, screen reader support)
