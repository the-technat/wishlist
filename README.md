# wishlist

Repo to deploy family wishlist

## Initial deploy

According to [this doc](https://fly.io/docs/launch/continuous-deployment-with-github-actions/):

- Before you deploy the app add some secrets:
  - `fly secrets set FLATNOTES_PASSWORD=<password> --stage`
  - `fly secrets set FLATNOTES_SECRET_KEY=<secret_key_here> --stage`
- A custom domain was provisioned according to [this doc](https://fly.io/docs/networking/custom-domain/) (after first deployment)
