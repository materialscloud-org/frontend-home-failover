# Static Materials Cloud homepage failover

Hosted via GitHub pages at https://materialscloud-org.github.io/frontend-home-failover

In order to use this site as the Materials Cloud failover:

1) Update the notification message in `index.html`
2) Change `CNAME` to `materialscloud.org`
3) Update the `A` apex (`@`) entry to point to the GitHub IP addresses:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

More information [here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain).

Archive failover instructions [here](https://docs.google.com/document/d/1811WB2ixUr2MHstkoF1n-Sg0KxLf3t0vz-11n9kE5JU/).