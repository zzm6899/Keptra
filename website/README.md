# Keptra landing page update

This patch adds the browser culling demo to the production website snapshot at `45d2d7a3c56474af5fb04dd68b0419b0ebc177a0`. It updates `web/index.html` and adds three assets under `web/assets/`.

From the website checkout, run `git apply --check` with the path to [`keptra-landing.patch`](keptra-landing.patch). Once the check passes, use `git apply` with the same path. For a file overlay, copy the three new assets into place before replacing `web/index.html`.
