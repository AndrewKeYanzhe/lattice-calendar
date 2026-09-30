# Lattice Calendar website

A static, dependency-free site for Lattice Calendar. Upload the files in this directory to the root of the public `lattice-calendar` repository.

## GitHub Pages

In repository Settings → Pages, choose **Deploy from a branch**, then the default branch and **/ (root)**. Once enabled, the expected address is `https://AndrewKeYanzhe.github.io/lattice-calendar/`.

OAuth URLs after successful publication:
- Homepage: `https://AndrewKeYanzhe.github.io/lattice-calendar/`
- Privacy: `https://AndrewKeYanzhe.github.io/lattice-calendar/privacy.html`
- Terms: `https://AndrewKeYanzhe.github.io/lattice-calendar/terms.html`

These URLs are expected, not confirmed live. Google acceptance of the free GitHub Pages subdomain has not been verified. Add the Google Search Console verification tag to the homepage head when Google provides it. Keep the policy aligned with the app when changing its data handling.

Preview: `python3 -m http.server 4173` from this directory.

No Google credentials, device calendar data, or app source files belong in this repository. The calendar illustration contains sample events only.
