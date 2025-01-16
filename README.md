# Tailwind CSS Hover Effect Not Working

This repository demonstrates an uncommon bug in Tailwind CSS where a hover effect does not work as expected.  The button element has the correct Tailwind classes applied, yet the hover state does not trigger the expected background color change.

## Bug Description

A simple button with Tailwind classes for a red background and a hover effect to change the background to a darker shade of red does not change color when hovered over.

## Bug Reproduction

1. Clone this repository.
2. Open `index.html` in your browser.
3. Observe that hovering over the button does not change its background color.

## Solution

The solution is provided in `bugSolution.js`.  The issue is likely caused by conflicting styles or an oversight in class application.  The solution file offers a fix addressing potential problems, such as unintended CSS overrides.