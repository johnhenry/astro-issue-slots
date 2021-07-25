# Astro Issue: slots

This example demonstrates an issue with the [Astro](https://astro.build).

When using multiple slots within components, rather that forwarding components to specific named slots, all content is copied to all avaliable slots.

Note: This example was constructed using the example [here](https://docs.astro.build/core-concepts/astro-components#slots).

1. Install and build this repository with `npm run install && npm run build`
2. Error! The content of `dist/actual/index.html` contains three copies of the content passed to MyComponent.
3. The content of `dist/actual/index.html` should resemble the content in `dist/public/expected.html`
