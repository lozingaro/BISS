# Bertinoro International Spring School

[Italian Computer Science PhD granting institutions](http://www.disi.unige.it/dottorato/coordinamento/) under the auspices of [GRIN](http://www.grin-informatica.it/), organizes an annual school offering three graduate-level courses aimed at first-year PhD students in Computer Science. 
In addition to introducing students to timely research topics, the school is meant to promote acquaintance and collaboration among young European researchers

BISS events are held in the University Residential Center located in the small medieval hilltop town of Bertinoro. 
This town is in Emilia Romagna about 50km east of Bologna at an elevation of 230m above sea level.

## About the repository

In the `src` folder, you can find the source code for the website that uses [Jekyll](https://jekyllrb.com) to produce the static web pages and place them under the destination defined in `_config.yml` --> `destination` path.

**This is to preserve the old versions of the website**.

For example, for the following `_config.yml`:

```yaml
destination: "../public_html/2023"
```

you will find the web pages in the folder `public_html/2023`.

### Build a new BISS web page

To build a **new** static web page, do the following:
1. [Fork the repository](https://github.com/lozingaro/BISS/fork);
2. Change `destination` in `_config.yml` with something like `../public_html/2024` (ensure the path exists);
3. Edit source code in `src` according to your needs;
4. [Open a `Pull Request`](https://github.com/lozingaro/BISS/compare) to update the repository.
