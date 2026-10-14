# balajisriramareddy.github.io

Source for my portfolio site, live at https://balajisriramareddy.github.io/

It's a single `index.html` with no build step. GitHub Pages serves it straight from the `main` branch.

## Projects on the site

| Case study | Repository |
|---|---|
| Zepto Inventory Analysis | [zepto-inventory-sql-analysis](https://github.com/BalajiSriramareddy/zepto-inventory-sql-analysis) |
| Databel Customer Churn Analysis | [databel-customer-churn-analysis](https://github.com/BalajiSriramareddy/databel-customer-churn-analysis) |
| Customer Behaviour Analysis | [customer_behaviour_analysis](https://github.com/BalajiSriramareddy/customer_behaviour_analysis) |
| Automated Data Cleaning and Validation System | [CadetX-Automated-Data-Cleaning-And-Validation-System](https://github.com/BalajiSriramareddy/CadetX-Automated-Data-Cleaning-And-Validation-System) |
| Heavy Supplier, Inventory and Warehouse Analytics | In progress |

## Updating it

Everything editable is in two blocks near the bottom of `index.html`:

- `SITE` holds contact links and the optional photo path.
- `PROJECTS` holds one entry per case study. Set `repo` to the repository name and the case-study page loads that repository's README live from GitHub, so the write-up on the site always matches the repo. The `body` text is only shown if the README can't be fetched.
- For a project still being built, set `status: "wip"` and update `sprintsDone` as each sprint is published.

Because the README is pulled in and rendered on the site, links inside project READMEs should be full `https://github.com/...` URLs. Relative links to files work on GitHub but break on the site.

Balaji Manjulamma Sriramareddy · [LinkedIn](https://www.linkedin.com/in/balaji-sriramareddy/) · balaji.manjulamma@gmail.com
