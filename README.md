# kaegi

Static site served by a Cloudflare Worker (static assets only, no Worker script).

- `public/index.html` — **Arnold Tongue Lab**: an interactive simulation comparing entrainment (noisy Adler phase oscillator) and superposition explanations of flicker-driven alpha oscillations, as discussed in Notbohm, Kurths & Herrmann (2016), *Front. Hum. Neurosci.* 10:10.

## Deploy

```sh
npx wrangler deploy
```

Local preview: `npx wrangler dev`.
