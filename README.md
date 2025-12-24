# CA-VA templates

Curriculum Aesthetic - Vitally Accessibile templates.

Making curriculums cute without forgetting about all our visually impaired internet friends.

## Requirements

- node

## How to (simple)

1. `git clone` this repo.
2. Execute `npm install`
3. Fill in `sample.json` with your data
4. If you wish to include a photo add it to the `out/assets` folder and add pathname to `sample.json`.
5. Execute `npm run pdf`

## How to (complex/custom)

If you wish to add features that are not available in the template I recommend you do steps 1-4 from the How to (simple) then.

5. Execute `npm run pdf:custom`
6. Edit the html to your liking in `out/document-ua.html`
7. Then `npm run build:pdf`.

## Check compliance

I would hope you don't blindly trust my program and want to check that it is actually accessible, so here are some free online resources:

- Checks that it meets PDF/UA && WCAG requirements: [axesCheck](https://check.axes4.com/en/)
- Checks that it meets WCAG color contrast AA & AAA levels on `Firefox`: [WCAG Color contrast checker](https://addons.mozilla.org/en-US/firefox/addon/wcag-contrast-checker/)
- Checks that it meets WCAG color contrast AA & AAA levels on `Chrome`: [WCAG Color contrast checker](https://chromewebstore.google.com/detail/wcag-color-contrast-check/plnahcmalebffmaghcpcmpaciebdhgdf?hl=es)
