# Contributing to Verso

Thanks for your interest!

## Ground rules
- **Zero runtime dependencies.** The whole app must stay a single self-contained `index.html`.
- **No build step.** It has to keep working by simply opening the file in a browser.
- Keep the public-domain web-safe font stacks; the only external resource is Google Fonts for the UI chrome.

## Running locally
There is nothing to build. Open `index.html`, or run `npx serve .`.

## Pull requests
- Keep changes focused and described clearly.
- Test the core round-trip: open a file → edit (move / resize / rotate / colors / text) → Download → reopen the result.
- For UI changes, check both desktop and a narrow (~380px) viewport.

## Ideas worth tackling
See the Roadmap in the README — undo/redo and `<style>`-rule editing are the highest-impact items.
