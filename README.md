# marky

## Editing Styles

__NEVER__ edit the CSS directly.
Only edit the Sass directory (`assets/sass`).

Make sure you have `sass` (via `gem`).

Then run:

```bash
$ sass --update assets/sass:assets/css
```

This converts the Sass code into CSS code.
