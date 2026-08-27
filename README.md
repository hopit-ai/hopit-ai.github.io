# hopit-ai.github.io

The landing page served at **[hopit-ai.github.io](https://hopit-ai.github.io/)**.
It introduces Hopit AI and points at both open benchmark suites:

- **[MODA](https://hopit-ai.github.io/Moda/)** — fashion retrieval and search
  ([code](https://github.com/hopit-ai/Moda))
- **[MODA_NER](https://hopit-ai.github.io/Moda_ner/)** — fashion attribute
  extraction ([code](https://github.com/hopit-ai/Moda_ner))

`index.html` is the page. It is a single self-contained file with no build step:
edit it and push, and GitHub Pages redeploys from `main`.

`coming-soon.html` is the 2025 launch page, kept for reference. It is no longer
linked from anywhere.

There is deliberately no `CNAME` file. `hopit.ai` is served from CloudFront, so a
CNAME here would claim that hostname as this site's custom domain and stop the
root from serving at all.
