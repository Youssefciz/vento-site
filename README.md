# ventotraining.com

Public site for the Vento iOS app. Deliberately a separate repository from the
app itself, which is private — GitHub Pages needs a public repo on the free plan.

    /                 landing page + support contact  (App Store "Support URL")
    /privacy/         privacy policy                  (App Store "Privacy Policy URL")

Static HTML, no build step. Edits go live on push via GitHub Pages.

`CNAME` binds the custom domain; deleting it unbinds the domain.
