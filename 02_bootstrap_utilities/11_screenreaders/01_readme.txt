Screenreaders

Screenreaders are used to hide an element to all devices except screen readers
with .sr-only. Combine .sr-only with .sr-only-focusable to show the element again when it?s
focused (e.g. by a keyboard-only user). Can also be used as mixins.

Syntax:

<a class="sr-only sr-only-focusable" href="#content">Skip to main content</a>

How to use it:

// Usage as a mixin
.skip-navigation {
  @include sr-only;
  @include sr-only-focusable;
}
