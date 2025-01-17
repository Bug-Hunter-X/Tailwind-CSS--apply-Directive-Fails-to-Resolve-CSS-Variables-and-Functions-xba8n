# Tailwind CSS @apply Directive Variable Resolution Bug

This repository demonstrates a bug where Tailwind CSS's `@apply` directive fails to correctly resolve CSS variables and functions used within custom styles. This can lead to unexpected styling behavior, where styles are either not applied or applied incorrectly.  The issue is present when using variables or functions within `@apply` directives.

## Bug Description

When using variables or functions within your custom CSS classes and applying them using the `@apply` directive, Tailwind CSS does not correctly interpret and resolve these values. This results in styles not being applied as expected.

## Solution

The recommended solution is to avoid using variables or functions directly within `@apply` directives. Instead, define your classes directly in your Tailwind configuration or use a CSS preprocessor for advanced variable and function handling.