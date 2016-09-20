# Grid

# Configuration

`$column__prefix`:
`$breakpoints`:

# Examples

```scss
.container-1 {
  margin: 0 auto;
  width: 500px;

  > .row {
    @include row(4, 30);
  }
}

.container-2 {
  margin: 0 auto;
  width: 1200px;

  > .row {
    @include row(10, 0);
  }
}
```
