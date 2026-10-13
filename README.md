# portfolio

A small static personal website, served from the repository root with GitHub Pages.

## Publish with GitHub Pages

In the repository's **Settings → Pages**, choose **Deploy from a branch**, then select the `main` branch and the `/ (root)` folder. Set `angusq.com` as the custom domain. Keep the root `CNAME` file set to `angusq.com`.

To support `www.angusq.com`, add a DNS record with your domain provider:

| Type | Name | Target |
| --- | --- | --- |
| CNAME | `www` | `angusquigley.github.io` |

Once the apex domain and `www` DNS records are configured, GitHub Pages redirects `www.angusq.com` to `angusq.com`. Do not add `www.angusq.com` to the repository's `CNAME` file. See [GitHub's custom domain documentation](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site) for the apex domain's DNS setup.

## Personalize the page

- Edit the About text and Qualifications section in `index.html` whenever you want to update them.
- The portrait is stored at `assets/profile.jpg`; replace that file to use a different photo.
- Update the page title or styles in `index.html` and `styles.css` as needed.
