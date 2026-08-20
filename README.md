# Buyer-Ready Demo Kit

Free Markdown templates for turning rough B2B product notes into a sales demo, plus the source for my small done-for-you demo service.

[Open the site](https://buyer-ready.aqutte.co.ke)

## The free kit

The [`templates`](templates) directory contains:

- discovery questions
- a demo storyline
- an objection-handling sheet
- a one-page proposal draft
- a follow-up email sequence

There is a filled example in [`samples/sample-demo-kit.md`](samples/sample-demo-kit.md). Everything is plain Markdown, so you can copy it into Google Docs or edit it without buying another tool.

## The service

I use the same templates to prepare a sales pack for one product and buyer. The current starter price is USD 75, or the equivalent in Kenyan shillings. Turnaround is 48 hours after I accept the request and receive the source material.

The useful inputs are a product description, the target buyer, the problem being sold, any current demo notes, and pricing if it exists.

[Open a request on GitHub](https://github.com/KigoJomo/buyer-ready-demo-kit/issues/new?template=demo-kit-request.yml) or email `hello@kigo.ke` with `Demo Kit Request` as the subject.

## Run the site

There is no build step. Open `index.html` directly or serve the directory with any static file server.

```bash
python -m http.server 8000
```

The site deploys as static HTML with `vercel.json`.

This is an independent side project and is not affiliated with an employer.
