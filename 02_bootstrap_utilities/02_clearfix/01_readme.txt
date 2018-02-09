Clearfix

Clearfix is used to easily clear floats by adding .clearfix to the parent element.
It utilizes the micro clearfix as popularized by Nicolas Gallagher. It can also be used as a mixin.

Syntax:

<div class="clearfix">...</div>
How to use in mixin
// Mixin itself
@mixin clearfix() {
  &::after {
    display: block;
    content: "";
    clear: both;
  }
}

// Usage as a mixin
.element {
  @include clearfix;
}


How to use Clearfix

Let's take an example to see how the clearfix can be used.
Without the clearfix the wrapping div would not span around the buttons which would cause a broken layout.

Syntax:

<div class="bg-info clearfix">
  <button class="btn btn-secondary float-left">Example Button floated left</button>
  <button class="btn btn-secondary float-right">Example Button floated right</button>
</div>
