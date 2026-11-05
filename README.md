# Personal Data Analysis Portfolio Project Website

My personal portfolio website, showcasing my data analytics and business intelligence projects.

**Live site:** [deniskusmahendra.github.io](https://deniskusmahendra.github.io)

## About

I'm Denis Sam Kusmahendra, a Data Analyst based in Jakarta, Indonesia. I work with SQL, spreadsheets, Python, Power BI and Tableau. This site collects my main projects in one place and links to the full write-up and code for each.

## Featured Projects

| Project | What it covers | Repository |
| --- | --- | --- |
| Demand Forecasting & Inventory Optimization | Holt-Winters forecasting and an ABC-XYZ inventory matrix to support replenishment planning | [View](https://github.com/deniskusmahendra/Demand-Forecasting-and-Inventory-Optimization) |
| Marketing Performance & Funnel Conversion | GA4 event data in BigQuery to find checkout drop-offs, conversion rates and marketing performance | [View](https://github.com/deniskusmahendra/Marketing-and-Conversion-Funnel) |
| Customer Retention & Segmentation Analysis | RFM segmentation and cohort analysis to find high-value customers and track retention | [View](https://github.com/deniskusmahendra/Customer-Retention-and-Segmentation) |
| Sales Performance & Business Dashboard | Interactive Power BI dashboard of sales KPIs, revenue trends and regional performance (Olist dataset) | [View](https://github.com/deniskusmahendra/Sales-Performance-Analysis) |
| YouTube: Data & BI Tools Tutorials | A 5-part SQL tutorial series using PostgreSQL and a fictional e-commerce database | [Channel](https://www.youtube.com/@deniskusmahendra) |

## Built With

- HTML and CSS, with no build step
- jQuery for the layout scripts
- Font Awesome icons
- [Strata](https://html5up.net/strata) template by HTML5 UP, customized
- Hosted on GitHub Pages

## Project Structure

```
.
├── index.html            # The whole site: sidebar, projects, contact, footer
├── images/               # Avatar and project thumbnails
└── assets/
    ├── css/
    │   ├── main.css      # Base template styles (compiled from sass/)
    │   └── custom.css    # My own layout, colour and typography changes
    ├── js/               # jQuery, template helpers and main.js
    ├── sass/             # Template source styles (not compiled by GitHub Pages)
    └── webfonts/         # Font Awesome font files
```

## Running Locally

No installation is needed. Clone the repository and open `index.html` in a browser:

```bash
git clone https://github.com/deniskusmahendra/deniskusmahendra.github.io.git
cd deniskusmahendra.github.io
```

Or serve it locally so it behaves like the live site:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Adding a New Project

1. Add a thumbnail image to `images/` (a landscape image works best).
2. In `index.html`, copy one of the `<article class="col-6 col-12-xsmall work-item">` blocks inside the Projects section.
3. Update the link, image path, alt text, title and description.
4. Commit and push to `main`. GitHub Pages publishes the change within a minute or two.

Style changes go in `assets/css/custom.css`, so the original template file stays untouched.

## Contact

- Email: [deniskusmahendra@gmail.com](mailto:deniskusmahendra@gmail.com)
- LinkedIn: [linkedin.com/in/deniskusmahendra](https://www.linkedin.com/in/deniskusmahendra)
- GitHub: [github.com/deniskusmahendra](https://github.com/deniskusmahendra)

## License and Credits

Site design is based on [Strata by HTML5 UP](https://html5up.net/strata), used under the [Creative Commons Attribution 3.0 license](https://html5up.net/license) (see `LICENSE.txt`). The content, project descriptions and images are my own.
