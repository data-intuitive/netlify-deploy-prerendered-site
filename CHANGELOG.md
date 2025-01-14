# Netlify Deploy Site v1.0.3

## BUG FIXES

* Install Netlify CLI if it is not already installed (PR #3).

# Netlify Deploy Site v1.0.2

## BUG FIXES

* Alternate solution for removing debug info from stdout (PR #2).

# Netlify Deploy Site v1.0.1

## BUG FIXES

* Fix issue where `netlify deploy` started outputting debug information to stdout.

# Netlify Deploy Site v1.0.0

Initial release.

Example usage:

```yaml
- name: Deploy to Netlify 🚀
  uses: data-intuitive/netlify-deploy-site@v1
  with:
    auth: ${{ secrets.NETLIFY_AUTH_TOKEN }}
    site: 'my-netlify-site'
    dir: '_site'
    prod: true
    message: 'Deploy production ${{ github.ref }}'
```

See the README for more information.
