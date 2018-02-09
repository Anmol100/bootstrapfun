Invisible Content

The .invisible class can be used to toggle only the visibility of an element,
meaning its display is not modified and the element can still affect the flow of the document.

Syntax:

<div class="invisible">...</div>

How to use it:

// Class
.invisible {
  visibility: hidden;
}
// Usage as a mixin
.element {
  @include invisible;
}
