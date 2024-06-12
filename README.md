# Deno for [pre-commit](https://pre-commit.com/)

Run `deno fmt` and `deno lint` in `pre-commit`! Before you get too excited, this requires `deno` to
be present on your system already.

### Hooks

- `deno-lint`: Runs `deno lint`
- `deno-fmt`: Runs `deno fmt --check`
- `deno-fmt-fix`: Runs `deno fmt` and writes fixes to non-compliant files. You could then generate
   a patch from those fixes through some other mechanism.
