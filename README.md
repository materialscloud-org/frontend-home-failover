# Static Materials Cloud homepage failover

Hosted via GitHub pages at https://materialscloud-org.github.io/frontend-home-failover

In order to use this site as the Materials Cloud failover:

1) Update the notification message in `index.html`
2) Change `CNAME` to `materialscloud.org`
3) Update the `A` apex (`@`) entry to point to the GitHub IP addresses (just one entry should be enough for a temporary failover):
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

To switch back to the CSCS server:

1) Revert the `A` apex (`@`) entry to point back.
2) Revert `CNAME` back to `failover.materialscloud.org`

More information [here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain).

Note: the https certificate may be enabled with some delay (~30 min). 

Archive failover instructions [here](https://docs.google.com/document/d/1811WB2ixUr2MHstkoF1n-Sg0KxLf3t0vz-11n9kE5JU/).
