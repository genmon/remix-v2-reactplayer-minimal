# remix-v2-reactplayer-minimal

Repro:

- Install [Remix](https://remix.run) with `npx create-remix@latest` -- this installs v2
- Install [react-player](https://github.com/CookPete/react-player)

Minimal use of `ReactPlayer` is in `app/routes/_index.tsx`.

Visiting the page in the browser produces an immediate Application Error:

```
Error: Element type is invalid: expected a string (for built-in components) or a class/function (for composite components) but got: object.
```
