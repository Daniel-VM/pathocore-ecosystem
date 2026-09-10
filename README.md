# pathocore-ecosystem

Landing page for the PathoCore ecosystem. Static site, no build step.

    index.html      the page
    assets/         institutional logos
    CNAME           custom domain for GitHub Pages

## Deploy

Push to the default branch, then enable **Settings → Pages → Deploy from a branch → main / (root)**.

The `CNAME` file requests the custom domain `pathocore-ecosystem.ciberisciii.es`.
It only works once IT creates this DNS record:

    pathocore-ecosystem   CNAME   biplat-ciberinfec.github.io.

Delete `CNAME` if you want to stay on the default `*.github.io` URL.
